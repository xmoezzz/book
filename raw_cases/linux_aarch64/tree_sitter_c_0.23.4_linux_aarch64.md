# `tree-sitter-c` `0.23.4`

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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
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
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1029573-1783999112111892440.map",
  "pid": 1029573,
  "ppid": 1029556,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1029573-1783999112111892440.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/libtree-sitter-c.a`

Owner: `tree-sitter-c` `0.23.4`

### Source files

* `/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4/src/parser.c`

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
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1029594,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 1029598,
  "ppid": 1029594,
  "root_cargo_pid": 1029317,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c11",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1029599,
  "ppid": 1029598,
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "root_cargo_pid": 1029317,
  "build_script_root_pid": 1029594,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
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
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/libtree-sitter-c.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/libtree-sitter-c.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 1029619,
  "ppid": 1029594,
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "root_cargo_pid": 1029317,
  "build_script_root_pid": 1029594,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
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
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "workspace_root": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4"
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
      "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
      "name": "tree-sitter-c",
      "version": "0.23.4",
      "manifest_path": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4"
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
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
  "pid": 1029367,
  "ppid": 1029332,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
  "event_id": "used:cc:d9861ad91616b5cc:be3cb04179b02052:085e3bf50b18abef",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
  "pid": 1029367,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
  "pid": 1029367,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
  "pid": 1029367,
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
  "context_path": "/tmp/native-trace-1029263-1783999109299/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1029263-1783999109299/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1029367,
  "ppid": 1029332,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty",
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
      "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-1029367-1783999111371681323.map",
  "pid": 1029367,
  "ppid": 1029332,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1029367-1783999111371681323.map"
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1029573,
  "ppid": 1029556,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:ac7421dee8567f95:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
  "pid": 1029573,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:8f66ba2dd01b3c09:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "b5b4c73b5e98641b5420e3af4c4593d70400e31d5da107af005aa54e57bd87a7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:92d2299caf7e6c53:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "53a70143cf03f14838b6b0d3c928cefe4f17877ff7d3032352384a468b04eda3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:98e7185df8e31fa3:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "6f1be75dda2249384979e790137b84579f62f8be67a3a1676c0b360a938e6b6a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:d6cecd6f4825a53f:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "14b4747dce93a23f04fa7b32c887d2403b5eca548401cade7d3b22c72f2c65b2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:53095cf50af0cff6:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "ff1d82d7cdad6cc05407bd7549e9185958b919c75666ff8133cc2453c72ac54b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:0afd30e4dfd2b607:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "e30367d4f588df56acb1b5f9bbab13d1ff19b4e576de0b880b44f6cf271ab40d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:d566a5312cc56138:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "3b05656f29bdc98a520d14f387ebfd8bf4f96f9b0623b30820bd12cc6dc98c99",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:a2b78fbe7cbebd51:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "c2274f767b8deb964c17809c62ba20dd1798a0516e565411ac66e3ddabd21283",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:e98bc92b2be59f14:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "984ec8c2dd563884e140116a4a9e1b74ae26d321a496e40406ab6a26845a4558",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:7bc8f34603bac7af:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "3471b8a7c08abae40fe65d071258b103c8c19647d7b5d2525d2e0af9640f1c83",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:bdfad4e736aedcbe:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "79b9eeb08daa52e29fe1ecbf257d50926d485e6572c10edf50a905589b334f5a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "used:cc:997318724d582c1b:f31f05980d92e559:d3fe372f36cbcf2f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
  "pid": 1029573,
  "sha256": "8b687b34059176d55800a347a3186df90df03539ecf7a571a12805324e02ee24",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "cargo_pkg_name": "tree-sitter-c",
  "cargo_pkg_version": "0.23.4",
  "context_path": "/tmp/native-trace-1029263-1783999109299/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1029263-1783999109299/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1029573,
  "ppid": 1029556,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u",
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
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
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1029573-1783999112111892440.map",
  "pid": 1029573,
  "ppid": 1029556,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1029573-1783999112111892440.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
  "parsed_event_count": 361,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 362,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "0010 1030009   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDYMMFd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.998   rustc            1030033 1029983   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n6.016   build-script-bu  1030039 1029983   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n6.019   rustc            1030041 1029983   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n6.417   runc             1030054 1019479   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84a --log-format json --systemd-cgroup kill --all f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84aa08fc 9\n6.434   runc             1030061 1019479   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84a --log-format json --systemd-cgroup delete f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84aa08fc\n6.573   rustc            1030080 1029983   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a4b83e88e0a2e5e1 ...\n6.612   cc               1030097 1030080   0 /tmp/native-trace-1029972-1783999115115/shims/cc -m64 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcRyxPlh/symbols.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.1g91vjw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n6.613   cc               1030098 1030097   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcRyxPlh/symbols.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.1g91vjw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n6.615   collect2         1030099 1030098   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoqji07.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n6.616   ld.lld           1030100 1030099   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoqji07.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc ...\n6.617   rust-lld         1030100 1030099   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoqji07.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n6.634   containerd-shim  1030118 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84aa08fc -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84a delete\n6.637   runc             1030124 1030118   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84aa08f --log-format json delete --force f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84aa08fc\n6.665   systemd-sysctl   1030130 1029877   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6e26836 --prefix=/net/ipv4/neigh/veth6e26836 --prefix=/net/ipv6/conf/veth6e26836 --prefix=/net/ipv6/neigh/veth6e26836\n6.673   build-script-bu  1030132 1029983   0 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build-script-build\n6.675   riscv64-linux-g  1030133 1030132   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/17347045287110676504detect_compiler_family.c\n6.676   cc1              1030134 1030133   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/17347045287110676504detect_compiler_family.c -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 17347045287110676504detect_compiler_family.c -dumpbase-ext .c\n6.682   riscv64-linux-g  1030135 1030132   0 /usr/bin/riscv64-linux-gnu-gcc -?\n6.684   riscv64-linux-g  1030136 1030132   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/ea708c7824d36062-parser.o -c src/parser.c\n6.685   cc1              1030137 1030136   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu src/parser.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/ -dumpbase ea708c7824d36062-parser.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n6.991   runc             1030138 1019780   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b13 --log-format json --systemd-cgroup kill --all 3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b1391c2c 9\n7.002   as               1030144 1030136   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/ea708c7824d36062-parser.o /tmp/ccj6xKms.s\n7.009   runc             1030145 1019780   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b13 --log-format json --systemd-cgroup delete 3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b1391c2c\n7.053   riscv64-linux-g  1030151 1030132   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/libtree-sitter-c.a /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/ea708c7824d36062-parser.o\n7.072   riscv64-linux-g  1030152 1030132   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/libtree-sitter-c.a\n7.092   rustc            1030154 1029983   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_c --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=f3b430cbf6636779 ...\n7.214   containerd-shim  1030161 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b1391c2c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b13 delete\n7.216   runc             1030168 1030161   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b1391c2 --log-format json delete --force 3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b1391c2c\n7.254   sh               1030175 1029877   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethb9e5feb\n7.255   ethtool          1030176 1030175   0 /usr/sbin/ethtool -i vethb9e5feb\n7.255   sed              1030177 1030175   0 /usr/bin/sed -n s/^driver: //p\n7.261   systemd-sysctl   1030180 1029877   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb9e5feb --prefix=/net/ipv4/neigh/vethb9e5feb --prefix=/net/ipv6/conf/vethb9e5feb --prefix=/net/ipv6/neigh/vethb9e5feb\n7.725   runc             1030181 1026945   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687f --log-format json --systemd-cgroup kill --all 95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687fc47fd 9\n7.742   runc             1030187 1026945   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687f --log-format json --systemd-cgroup delete 95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687fc47fd\n7.925   containerd-shim  1030194 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687fc47fd -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687f delete\n7.928   runc             1030200 1030194   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687fc47f --log-format json delete --force 95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687fc47fd\n7.960   systemd-sysctl   1030206 1029877   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf154e49 --prefix=/net/ipv4/neigh/vethf154e49 --prefix=/net/ipv6/conf/vethf154e49 --prefix=/net/ipv6/neigh/vethf154e49\n8.795   cross            1030207 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n8.796   rustc            1030210 1030207   0 /home/xmoe/.cargo/bin/rustc --print target-list\n8.803   rustc            1030210 1030207   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n8.818   rustc            1030222 1030207   0 /home/xmoe/.cargo/bin/rustc -vV\n8.826   rustc            1030222 1030207   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.837   cargo            1030232 1030207   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n8.844   cargo            1030232 1030207   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n8.856   rustc            1030241 1030232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.869   rustc            1030243 1030232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.884   rustc            1030247 1030232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n9.006   rustc            1030252 1030232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.034   rustc            1030254 1030207   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n9.041   rustc            1030254 1030207   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n9.054   docker           1030266 1030207   0 /usr/bin/docker --help\n9.069   docker           1030276 1030207   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n9.083   runc             1030288 1599     0 /usr/bin/runc --version\n9.086   docker-init      1030294 1599     0 /usr/bin/docker-init --version\n9.087   docker           1030295 1030207   0 /usr/bin/docker info -f {{.SecurityOptions}}\n9.100   runc             1030306 1599     0 /usr/bin/runc --version\n9.104   docker-init      1030312 1599     0 /usr/bin/docker-init --version\n9.132   rustup           1030313 1030207   0 /home/xmoe/.cargo/bin/rustup toolchain list\n9.139   rustup           1030322 1030207   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n9.168   rustup           1030331 1030207   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n9.198   uname            1030340 1030207   0 /usr/bin/uname -r\n9.219   docker           1030341 1030207   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n9.259   systemd-sysctl   1030353 1029877   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2d91a14 --prefix=/net/ipv4/neigh/veth2d91a14 --prefix=/net/ipv6/conf/veth2d91a14 --prefix=/net/ipv6/neigh/veth2d91a14\n9.259   systemd-sysctl   1030352 1029893   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethef608e3 --prefix=/net/ipv4/neigh/vethef608e3 --prefix=/net/ipv6/conf/vethef608e3 --prefix=/net/ipv6/neigh/vethef608e3\n9.273   containerd-shim  1030354 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f2a570 start\n9.275   containerd-shim  1030360 1030354   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f2a570 -address /var/run/docker/containerd/containerd.sock\n9.280   runc             1030371 1030360   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f2a570\n9.285   exe              1030379 1030371   0 /proc/self/exe init\n9.315   exe              1030388 1030371   0 /proc/1599/exe -exec-root=/var/run/docker cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f2a570 d7da31e8f8e1\n9.333   exe              1030396 1599     0 /proc/self/exe /var/run/docker/netns/d5ded09db55c all false\n9.383   runc             1030415 1030360   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f --log-format json --systemd-cgroup start cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f2a570\n9.388   sh               1030382 1030360   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n9.389   cargo            1030421 1030382   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n9.399   cargo-native-tr  1030421 1030382   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n9.402   cargo            1030426 1030421   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n9.411   rustc            1030427 1030426   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.421   rustc            1030429 1030426   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n9.441   execsnoop        1030433 1030421   0 /usr/local/bin/execsnoop -t\n9.441   python3          1030433 1030421   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n9.852   runc             1030436 1023293   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab --log-format json --systemd-cgroup kill --all fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab0ccb4 9\n9.868   runc             1030442 1023293   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab --log-format json --systemd-cgroup delete fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab0ccb4\n9.948   runc             1030448 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2718324463 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n9.952   exe              1030456 1030448   0 /proc/self/exe init\n9.975   curl             1030458 1030448   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n10.067  containerd-shim  1030464 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab0ccb4 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab delete\n10.069  runc             1030471 1030464   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab0ccb --log-format json delete --force fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab0ccb4\n10.099  systemd-sysctl   1030476 1029877   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetheae0e1b --prefix=/net/ipv4/neigh/vetheae0e1b --prefix=/net/ipv6/conf/vetheae0e1b --prefix=/net/ipv6/neigh/vetheae0e1b\n11.162  cargo            1030478 1030421   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n11.174  rustc            1030479 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.191  rustc            1030488 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n11.191  rustc            1030487 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n11.192  rustc            1030489 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n11.233  cc               1030502 1030489   0 /tmp/native-trace-1030421-1783999120584/shims/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuHwtLE/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.234  cc               1030503 1030502   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuHwtLE/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.236  collect2         1030504 1030503   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwGiXWY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.237  ld.lld           1030505 1030504   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwGiXWY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ...\n11.238  rust-lld         1030505 1030504   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwGiXWY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.257  rustc            1030528 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n11.274  build-script-bu  1030534 1030478   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n11.276  rustc            1030536 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n11.830  rustc            1030563 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a4b83e88e0a2e5e1 ...\n11.871  cc               1030580 1030563   0 /tmp/native-trace-1030421-1783999120584/shims/cc -m64 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcwhxzf4/symbols.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.0kjm42n.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n11.871  cc               1030581 1030580   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcwhxzf4/symbols.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.0kjm42n.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n11.874  collect2         1030582 1030581   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVolN6V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.875  ld.lld           1030583 1030582   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVolN6V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc ...\n11.876  rust-lld         1030583 1030582   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVolN6V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.931  build-script-bu  1030601 1030478   0 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build-script-build\n11.933  powerpc64le-lin  1030602 1030601   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/2568180747844581469detect_compiler_family.c\n11.934  cc1              1030603 1030602   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/2568180747844581469detect_compiler_family.c -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n11.938  powerpc64le-lin  1030604 1030601   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n11.941  powerpc64le-lin  1030605 1030601   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/ea708c7824d36062-parser.o -c src/parser.c\n11.942  cc1              1030606 1030605   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I src -imultiarch powerpc64le-linux-gnu src/parser.c -msecure-plt -quiet -dumpbase parser.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/ea708c7824d36062-parser.o -g -gdwarf-4 -O0 -Wall -Wextra ...\n12.247  as               1030607 1030605   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I src -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/ea708c7824d36062-parser.o /tmp/ccEWQd1J.s\n12.288  powerpc64le-lin  1030608 1030601   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/libtree-sitter-c.a /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/ea708c7824d36062-parser.o\n12.290  powerpc64le-lin  1030609 1030601   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/libtree-sitter-c.a\n12.295  rustc            1030611 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_c --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ead31c8f41a81440 ...\n15.465  16               1030618 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n15.476  frpc             1030618 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n15.748  cross            1030625 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.749  rustc            1030628 1030625   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.756  rustc            1030628 1030625   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.770  rustc            1030640 1030625   0 /home/xmoe/.cargo/bin/rustc -vV\n15.777  rustc            1030640 1030625   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.788  cargo            1030650 1030625   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.795  cargo            1030650 1030625   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.808  rustc            1030659 1030650   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.820  rustc            1030661 1030650   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.835  rustc            1030665 1030650   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.867  rustc            1030669 1030625   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.874  rustc            1030669 1030625   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.888  docker           1030681 1030625   0 /usr/bin/docker --help\n15.903  docker           1030694 1030625   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.917  runc             1030705 1599     0 /usr/bin/runc --version\n15.920  cross            1030711 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n15.920  docker-init      1030713 1599     0 /usr/bin/docker-init --version\n15.922  docker           1030716 1030625   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.922  rustc            1030715 1030711   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.928  rustc            1030715 1030711   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.935  runc             1030735 1599     0 /usr/bin/runc --version\n15.939  docker-init      1030744 1599     0 /usr/bin/docker-init --version\n15.942  rustc            1030748 1030711   0 /home/xmoe/.cargo/bin/rustc -vV\n15.948  rustc            1030748 1030711   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.959  cargo            1030758 1030711   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.966  cargo            1030758 1030711   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.966  rustup           1030767 1030625   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.972  rustup           1030776 1030625   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.979  rustc            1030785 1030758   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.991  rustc            1030787 1030758   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.002  rustup           1030791 1030625   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.006  rustc            1030800 1030758   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.028  rustc            1030804 1030711   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.031  uname            1030805 1030625   0 /usr/bin/uname -r\n16.035  rustc            1030804 1030711   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.049  docker           1030817 1030711   0 /usr/bin/docker --help\n16.052  docker           1030823 1030625   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.064  docker           1030839 1030711   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.078  runc             1030852 1599     0 /usr/bin/runc --version\n16.081  docker-init      1030858 1599     0 /usr/bin/docker-init --version\n16.082  docker           1030859 1030711   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.096  runc             1030871 1599     0 /usr/bin/runc --version\n16.100  docker-init      1030877 1599     0 /usr/bin/docker-init --version\n16.125  rustup           1030878 1030711   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.133  rustup           1030887 1030711   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.154  systemd-sysctl   1030898 1030896   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9801767 --prefix=/net/ipv4/neigh/veth9801767 --prefix=/net/ipv6/conf/veth9801767 --prefix=/net/ipv6/neigh/veth9801767\n16.156  systemd-sysctl   1030899 1030897   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdcc2df3 --prefix=/net/ipv4/neigh/vethdcc2df3 --prefix=/net/ipv6/conf/vethdcc2df3 --prefix=/net/ipv6/neigh/vethdcc2df3\n16.167  rustup           1030920 1030711   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.170  containerd-shim  1030927 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35fb4ca start\n16.173  containerd-shim  1030947 1030927   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35fb4ca -address /var/run/docker/containerd/containerd.sock\n16.177  runc             1030956 1030947   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35 bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35fb4ca\n16.184  exe              1030963 1030956   0 /proc/self/exe init\n16.199  uname            1030965 1030711   0 /usr/bin/uname -r\n16.220  docker           1030973 1030711   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.226  exe              1030979 1030956   0 /proc/1599/exe -exec-root=/var/run/docker bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35fb4ca d7da31e8f8e1\n16.253  exe              1030996 1599     0 /proc/self/exe /var/run/docker/netns/0cbd66f26903 all false\n16.260  systemd-sysctl   1031002 1030918   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8013506 --prefix=/net/ipv4/neigh/veth8013506 --prefix=/net/ipv6/conf/veth8013506 --prefix=/net/ipv6/neigh/veth8013506\n16.260  systemd-sysctl   1031003 1030921   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3aeaf22 --prefix=/net/ipv4/neigh/veth3aeaf22 --prefix=/net/ipv6/conf/veth3aeaf22 --prefix=/net/ipv6/neigh/veth3aeaf22\n16.279  containerd-shim  1031010 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e66d7f start\n16.283  containerd-shim  1031020 1031010   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e66d7f -address /var/run/docker/containerd/containerd.sock\n16.286  runc             1031029 1031020   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e 78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e66d7f\n16.293  exe              1031036 1031029   0 /proc/self/exe init\n16.316  runc             1031047 1030947   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35 --log-format json --systemd-cgroup start bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35fb4ca\n16.322  sh               1030967 1030947   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.323  cargo            1031053 1030967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.335  exe              1031054 1031029   0 /proc/1599/exe -exec-root=/var/run/docker 78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e66d7f d7da31e8f8e1\n16.337  cargo-native-tr  1031053 1030967   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.341  cargo            1031060 1031053   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.355  rustc            1031063 1031060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.361  exe              1031064 1599     0 /proc/self/exe /var/run/docker/netns/dd7df7f934f1 all false\n16.365  cross            1031071 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n16.366  rustc            1031074 1031071   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.368  rustc            1031075 1031060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.372  rustc            1031074 1031071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.387  rustc            1031103 1031071   0 /home/xmoe/.cargo/bin/rustc -vV\n16.393  rustc            1031103 1031071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.403  execsnoop        1031113 1031053   0 /usr/local/bin/execsnoop -t\n16.404  python3          1031113 1031053   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.404  cargo            1031116 1031071   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.411  cargo            1031116 1031071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.420  runc             1031127 1031020   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e --log-format json --systemd-cgroup start 78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e66d7f\n16.425  sh               1031040 1031020   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.426  rustc            1031133 1031116   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.427  cargo            1031134 1031040   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.437  rustc            1031136 1031116   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.440  cargo-native-tr  1031134 1031040   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.444  cargo            1031137 1031134   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.451  rustc            1031141 1031116   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.457  rustc            1031142 1031137   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.467  rustc            1031147 1031137   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.470  rustc            1031148 1031071   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.475  rustc            1031148 1031071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.485  docker           1031163 1031071   0 /usr/bin/docker --help\n16.489  execsnoop        1031169 1031134   0 /usr/local/bin/execsnoop -t\n16.489  python3          1031169 1031134   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.497  docker           1031177 1031071   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.508  runc             1031185 1599     0 /usr/bin/runc --version\n16.510  docker-init      1031191 1599     0 /usr/bin/docker-init --version\n16.511  docker           1031192 1031071   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.522  runc             1031203 1599     0 /usr/bin/runc --version\n16.526  docker-init      1031209 1599     0 /usr/bin/docker-init --version\n16.546  rustup           1031210 1031071   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.552  rustup           1031219 1031071   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.574  rustup           1031228 1031071   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.596  uname            1031237 1031071   0 /usr/bin/uname -r\n16.612  docker           1031238 1031071   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.663  systemd-sysctl   1031253 1030921   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0a0b46a --prefix=/net/ipv4/neigh/veth0a0b46a --prefix=/net/ipv6/conf/veth0a0b46a --prefix=/net/ipv6/neigh/veth0a0b46a\n16.663  systemd-sysctl   1031252 1030918   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc6ab637 --prefix=/net/ipv4/neigh/vethc6ab637 --prefix=/net/ipv6/conf/vethc6ab637 --prefix=/net/ipv6/neigh/vethc6ab637\n16.678  containerd-shim  1031254 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda438467941 start\n16.681  containerd-shim  1031260 1031254   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda438467941 -address /var/run/docker/containerd/containerd.sock\n16.684  runc             1031270 1031260   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda4384 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda4384 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda4384 cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda438467941\n16.689  exe              1031278 1031270   0 /proc/self/exe init\n16.724  exe              1031286 1031270   0 /proc/1599/exe -exec-root=/var/run/docker cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda438467941 d7da31e8f8e1\n16.744  exe              1031295 1599     0 /proc/self/exe /var/run/docker/netns/1052dc6bb427 all false\n16.788  runc             1031314 1031260   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda4384 --log-format json --systemd-cgroup start cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda438467941\n16.793  sh               1031280 1031260   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.794  cargo            1031320 1031280   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n16.803  cargo-native-tr  1031320 1031280   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n16.806  cargo            1031321 1031320   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.816  rustc            1031322 1031321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.826  rustc            1031324 1031321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.847  execsnoop        1031328 1031320   0 /usr/local/bin/execsnoop -t\n16.848  python3          1031328 1031320   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.253  runc             1031331 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1639587015 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n18.258  exe              1031339 1031331   0 /proc/self/exe init\n18.286  etcdctl          1031341 1031331   0 /usr/local/bin/etcdctl endpoint health\n18.324  cargo            1031356 1031134   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n18.336  rustc            1031357 1031356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.356  rustc            1031367 1031356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.152/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n18.357  rustc            1031365 1031356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=3b393852d2f0042a ...\n18.357  rustc            1031368 1031356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.79/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=5b7572f701307434 ...\n18.357  rustc            1031369 1031356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"rustc-dep-of-std\")) -C metadata=44346b50c4e9393e ...\n"
}
```

#### Record 28

```json
{
  "argv": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1029411,
  "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
  "pid": 1029411,
  "ppid": 1029317,
  "root_cargo_pid": 1029317,
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
    "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1029594,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build-script-build",
  "pid": 1029594,
  "ppid": 1029317,
  "root_cargo_pid": 1029317,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out"
}
```

#### Record 30

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-E",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/138872970189759799detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1029594,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 1029595,
  "ppid": 1029594,
  "root_cargo_pid": 1029317,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/138872970189759799detect_compiler_family.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1029594,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 1029596,
  "ppid": 1029595,
  "root_cargo_pid": 1029317,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
  "build_script_root_pid": 1029594,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 1029597,
  "ppid": 1029594,
  "root_cargo_pid": 1029317,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1029594,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 1029598,
  "ppid": 1029594,
  "root_cargo_pid": 1029317,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c11",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1029594,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 1029599,
  "ppid": 1029598,
  "root_cargo_pid": 1029317,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o",
    "/tmp/ccmw6jAz.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1029594,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 1029618,
  "ppid": 1029598,
  "root_cargo_pid": 1029317,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 36

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/libtree-sitter-c.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1029594,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 1029619,
  "ppid": 1029594,
  "root_cargo_pid": 1029317,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 37

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "sD",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/libtree-sitter-c.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1029594,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 1029620,
  "ppid": 1029594,
  "root_cargo_pid": 1029317,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
  "crate": "tree-sitter-c",
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "event_id": "bsrun:c65d634499ab6877:f3e62e358bbf8c4b:9ce2aa4c2c50ab9d",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
  "success": true,
  "target": null,
  "version": "0.23.4",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c11",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1029599,
  "ppid": 1029598,
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "root_cargo_pid": 1029317,
  "build_script_root_pid": 1029594,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
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
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/libtree-sitter-c.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/libtree-sitter-c.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 1029619,
  "ppid": 1029594,
  "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "root_cargo_pid": 1029317,
  "build_script_root_pid": 1029594,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
  "_owner": {
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
    "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T03:18:54.939197+00:00",
  "crate": "tree-sitter-c",
  "version": "0.23.4",
  "architecture": "aarch64",
  "duration_seconds": 30.17546012531966,
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
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "manifest_path": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4/Cargo.toml"
      }
    ],
    "attributed_event_count": 27,
    "unattributed_event_count": 12,
    "owners": [
      {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
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
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "workspace_root": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4"
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
          "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
          "name": "tree-sitter-c",
          "version": "0.23.4",
          "manifest_path": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4"
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
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
      "pid": 1029367,
      "ppid": 1029332,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
      "event_id": "used:cc:d9861ad91616b5cc:be3cb04179b02052:085e3bf50b18abef",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
      "pid": 1029367,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
      "pid": 1029367,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
      "pid": 1029367,
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
      "context_path": "/tmp/native-trace-1029263-1783999109299/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1029263-1783999109299/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1029367,
      "ppid": 1029332,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/raw-dylibs",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty",
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
          "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcPwSJty/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-1029367-1783999111371681323.map",
      "pid": 1029367,
      "ppid": 1029332,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1029367-1783999111371681323.map"
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1029573,
      "ppid": 1029556,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:ac7421dee8567f95:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
      "pid": 1029573,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:8f66ba2dd01b3c09:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "b5b4c73b5e98641b5420e3af4c4593d70400e31d5da107af005aa54e57bd87a7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:92d2299caf7e6c53:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "53a70143cf03f14838b6b0d3c928cefe4f17877ff7d3032352384a468b04eda3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:98e7185df8e31fa3:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "6f1be75dda2249384979e790137b84579f62f8be67a3a1676c0b360a938e6b6a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:d6cecd6f4825a53f:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "14b4747dce93a23f04fa7b32c887d2403b5eca548401cade7d3b22c72f2c65b2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:53095cf50af0cff6:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "ff1d82d7cdad6cc05407bd7549e9185958b919c75666ff8133cc2453c72ac54b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:0afd30e4dfd2b607:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "e30367d4f588df56acb1b5f9bbab13d1ff19b4e576de0b880b44f6cf271ab40d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:d566a5312cc56138:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "3b05656f29bdc98a520d14f387ebfd8bf4f96f9b0623b30820bd12cc6dc98c99",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:a2b78fbe7cbebd51:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "c2274f767b8deb964c17809c62ba20dd1798a0516e565411ac66e3ddabd21283",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:e98bc92b2be59f14:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "984ec8c2dd563884e140116a4a9e1b74ae26d321a496e40406ab6a26845a4558",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:7bc8f34603bac7af:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "3471b8a7c08abae40fe65d071258b103c8c19647d7b5d2525d2e0af9640f1c83",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:bdfad4e736aedcbe:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "79b9eeb08daa52e29fe1ecbf257d50926d485e6572c10edf50a905589b334f5a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "used:cc:997318724d582c1b:f31f05980d92e559:d3fe372f36cbcf2f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
      "pid": 1029573,
      "sha256": "8b687b34059176d55800a347a3186df90df03539ecf7a571a12805324e02ee24",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
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
      "output": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "cargo_pkg_name": "tree-sitter-c",
      "cargo_pkg_version": "0.23.4",
      "context_path": "/tmp/native-trace-1029263-1783999109299/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1029263-1783999109299/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1029573,
      "ppid": 1029556,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u",
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
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
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcPOxj9u/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.15o49in.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.15o49in.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.15o49in.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.15o49in.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.15o49in.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.15o49in.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.15o49in.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.15o49in.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.15o49in.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.15o49in.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.15o49in.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.15o49in.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-1029573-1783999112111892440.map",
      "pid": 1029573,
      "ppid": 1029556,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1029573-1783999112111892440.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
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
      "parsed_event_count": 361,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 362,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "0010 1030009   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDYMMFd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.998   rustc            1030033 1029983   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n6.016   build-script-bu  1030039 1029983   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n6.019   rustc            1030041 1029983   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n6.417   runc             1030054 1019479   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84a --log-format json --systemd-cgroup kill --all f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84aa08fc 9\n6.434   runc             1030061 1019479   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84a --log-format json --systemd-cgroup delete f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84aa08fc\n6.573   rustc            1030080 1029983   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a4b83e88e0a2e5e1 ...\n6.612   cc               1030097 1030080   0 /tmp/native-trace-1029972-1783999115115/shims/cc -m64 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcRyxPlh/symbols.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.1g91vjw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n6.613   cc               1030098 1030097   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcRyxPlh/symbols.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.1g91vjw.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.1g91vjw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n6.615   collect2         1030099 1030098   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoqji07.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n6.616   ld.lld           1030100 1030099   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoqji07.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc ...\n6.617   rust-lld         1030100 1030099   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoqji07.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n6.634   containerd-shim  1030118 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84aa08fc -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84a delete\n6.637   runc             1030124 1030118   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84aa08f --log-format json delete --force f437cde34d46d27c1dd7670c875d33b66fb174e5f06093a649c1f33e84aa08fc\n6.665   systemd-sysctl   1030130 1029877   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6e26836 --prefix=/net/ipv4/neigh/veth6e26836 --prefix=/net/ipv6/conf/veth6e26836 --prefix=/net/ipv6/neigh/veth6e26836\n6.673   build-script-bu  1030132 1029983   0 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build-script-build\n6.675   riscv64-linux-g  1030133 1030132   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/17347045287110676504detect_compiler_family.c\n6.676   cc1              1030134 1030133   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/17347045287110676504detect_compiler_family.c -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 17347045287110676504detect_compiler_family.c -dumpbase-ext .c\n6.682   riscv64-linux-g  1030135 1030132   0 /usr/bin/riscv64-linux-gnu-gcc -?\n6.684   riscv64-linux-g  1030136 1030132   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/ea708c7824d36062-parser.o -c src/parser.c\n6.685   cc1              1030137 1030136   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu src/parser.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/ -dumpbase ea708c7824d36062-parser.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n6.991   runc             1030138 1019780   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b13 --log-format json --systemd-cgroup kill --all 3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b1391c2c 9\n7.002   as               1030144 1030136   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/ea708c7824d36062-parser.o /tmp/ccj6xKms.s\n7.009   runc             1030145 1019780   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b13 --log-format json --systemd-cgroup delete 3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b1391c2c\n7.053   riscv64-linux-g  1030151 1030132   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/libtree-sitter-c.a /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/ea708c7824d36062-parser.o\n7.072   riscv64-linux-g  1030152 1030132   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-babf3b8807a921ea/out/libtree-sitter-c.a\n7.092   rustc            1030154 1029983   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_c --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=f3b430cbf6636779 ...\n7.214   containerd-shim  1030161 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b1391c2c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b13 delete\n7.216   runc             1030168 1030161   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b1391c2 --log-format json delete --force 3beb7f13554ba21e74ca794cb1def9ed6ddc38d5a1f9d98a0fea0143b1391c2c\n7.254   sh               1030175 1029877   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethb9e5feb\n7.255   ethtool          1030176 1030175   0 /usr/sbin/ethtool -i vethb9e5feb\n7.255   sed              1030177 1030175   0 /usr/bin/sed -n s/^driver: //p\n7.261   systemd-sysctl   1030180 1029877   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb9e5feb --prefix=/net/ipv4/neigh/vethb9e5feb --prefix=/net/ipv6/conf/vethb9e5feb --prefix=/net/ipv6/neigh/vethb9e5feb\n7.725   runc             1030181 1026945   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687f --log-format json --systemd-cgroup kill --all 95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687fc47fd 9\n7.742   runc             1030187 1026945   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687f --log-format json --systemd-cgroup delete 95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687fc47fd\n7.925   containerd-shim  1030194 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687fc47fd -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687f delete\n7.928   runc             1030200 1030194   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687fc47f --log-format json delete --force 95d9ce60177778923e0e935ef9499754dd24db4234eeac6ccef4254687fc47fd\n7.960   systemd-sysctl   1030206 1029877   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf154e49 --prefix=/net/ipv4/neigh/vethf154e49 --prefix=/net/ipv6/conf/vethf154e49 --prefix=/net/ipv6/neigh/vethf154e49\n8.795   cross            1030207 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n8.796   rustc            1030210 1030207   0 /home/xmoe/.cargo/bin/rustc --print target-list\n8.803   rustc            1030210 1030207   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n8.818   rustc            1030222 1030207   0 /home/xmoe/.cargo/bin/rustc -vV\n8.826   rustc            1030222 1030207   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.837   cargo            1030232 1030207   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n8.844   cargo            1030232 1030207   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n8.856   rustc            1030241 1030232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.869   rustc            1030243 1030232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.884   rustc            1030247 1030232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n9.006   rustc            1030252 1030232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.034   rustc            1030254 1030207   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n9.041   rustc            1030254 1030207   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n9.054   docker           1030266 1030207   0 /usr/bin/docker --help\n9.069   docker           1030276 1030207   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n9.083   runc             1030288 1599     0 /usr/bin/runc --version\n9.086   docker-init      1030294 1599     0 /usr/bin/docker-init --version\n9.087   docker           1030295 1030207   0 /usr/bin/docker info -f {{.SecurityOptions}}\n9.100   runc             1030306 1599     0 /usr/bin/runc --version\n9.104   docker-init      1030312 1599     0 /usr/bin/docker-init --version\n9.132   rustup           1030313 1030207   0 /home/xmoe/.cargo/bin/rustup toolchain list\n9.139   rustup           1030322 1030207   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n9.168   rustup           1030331 1030207   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n9.198   uname            1030340 1030207   0 /usr/bin/uname -r\n9.219   docker           1030341 1030207   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n9.259   systemd-sysctl   1030353 1029877   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2d91a14 --prefix=/net/ipv4/neigh/veth2d91a14 --prefix=/net/ipv6/conf/veth2d91a14 --prefix=/net/ipv6/neigh/veth2d91a14\n9.259   systemd-sysctl   1030352 1029893   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethef608e3 --prefix=/net/ipv4/neigh/vethef608e3 --prefix=/net/ipv6/conf/vethef608e3 --prefix=/net/ipv6/neigh/vethef608e3\n9.273   containerd-shim  1030354 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f2a570 start\n9.275   containerd-shim  1030360 1030354   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f2a570 -address /var/run/docker/containerd/containerd.sock\n9.280   runc             1030371 1030360   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f2a570\n9.285   exe              1030379 1030371   0 /proc/self/exe init\n9.315   exe              1030388 1030371   0 /proc/1599/exe -exec-root=/var/run/docker cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f2a570 d7da31e8f8e1\n9.333   exe              1030396 1599     0 /proc/self/exe /var/run/docker/netns/d5ded09db55c all false\n9.383   runc             1030415 1030360   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f --log-format json --systemd-cgroup start cd2c1c1a75f021fd0a522001549bd73a26a4dd7a02b42a52f1188358b1f2a570\n9.388   sh               1030382 1030360   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n9.389   cargo            1030421 1030382   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n9.399   cargo-native-tr  1030421 1030382   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n9.402   cargo            1030426 1030421   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n9.411   rustc            1030427 1030426   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.421   rustc            1030429 1030426   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n9.441   execsnoop        1030433 1030421   0 /usr/local/bin/execsnoop -t\n9.441   python3          1030433 1030421   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n9.852   runc             1030436 1023293   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab --log-format json --systemd-cgroup kill --all fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab0ccb4 9\n9.868   runc             1030442 1023293   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab --log-format json --systemd-cgroup delete fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab0ccb4\n9.948   runc             1030448 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2718324463 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n9.952   exe              1030456 1030448   0 /proc/self/exe init\n9.975   curl             1030458 1030448   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n10.067  containerd-shim  1030464 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab0ccb4 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab delete\n10.069  runc             1030471 1030464   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab0ccb --log-format json delete --force fa495f940eab9ce93deb3d2438cf1ab5715161b46589242d504c23857ab0ccb4\n10.099  systemd-sysctl   1030476 1029877   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetheae0e1b --prefix=/net/ipv4/neigh/vetheae0e1b --prefix=/net/ipv6/conf/vetheae0e1b --prefix=/net/ipv6/neigh/vetheae0e1b\n11.162  cargo            1030478 1030421   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n11.174  rustc            1030479 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.191  rustc            1030488 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n11.191  rustc            1030487 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n11.192  rustc            1030489 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n11.233  cc               1030502 1030489   0 /tmp/native-trace-1030421-1783999120584/shims/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuHwtLE/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.234  cc               1030503 1030502   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuHwtLE/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.236  collect2         1030504 1030503   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwGiXWY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.237  ld.lld           1030505 1030504   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwGiXWY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ...\n11.238  rust-lld         1030505 1030504   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwGiXWY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.257  rustc            1030528 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n11.274  build-script-bu  1030534 1030478   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n11.276  rustc            1030536 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n11.830  rustc            1030563 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a4b83e88e0a2e5e1 ...\n11.871  cc               1030580 1030563   0 /tmp/native-trace-1030421-1783999120584/shims/cc -m64 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcwhxzf4/symbols.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.0kjm42n.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n11.871  cc               1030581 1030580   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/rustcwhxzf4/symbols.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.03948hfpv06s3pl09obxotklp.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.0r3ocuhieyl5m9fpsdo35epwv.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.1qy7b7v30urun0m5oqe8rsfzm.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.45d355ntzoquym6n027xeyh0i.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.4bdkyfsg7cazi55s5i3lzdkp0.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.50qhlpjw2arbe3t7dcdaqetix.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6d6e6wdci4zfxbpczet8hv1he.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.6orpp5sl8zg6cbl43qi0pg791.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.7k7k0o6flxp5nd5d5f3uiorpk.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.aunzp9bdgx3tzqryuhi853uyw.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.c4pswgokqrbbdistjyhl7oabj.0kjm42n.rcgu.o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc.bhuwn4b56898xu0vusch3weti.0kjm42n.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n11.874  collect2         1030582 1030581   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVolN6V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.875  ld.lld           1030583 1030582   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVolN6V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build_script_build-a5737ebafafa61cc ...\n11.876  rust-lld         1030583 1030582   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVolN6V.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.931  build-script-bu  1030601 1030478   0 /target/debug/build/tree-sitter-c-a5737ebafafa61cc/build-script-build\n11.933  powerpc64le-lin  1030602 1030601   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/2568180747844581469detect_compiler_family.c\n11.934  cc1              1030603 1030602   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/2568180747844581469detect_compiler_family.c -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n11.938  powerpc64le-lin  1030604 1030601   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n11.941  powerpc64le-lin  1030605 1030601   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -std=c11 -I src -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/ea708c7824d36062-parser.o -c src/parser.c\n11.942  cc1              1030606 1030605   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I src -imultiarch powerpc64le-linux-gnu src/parser.c -msecure-plt -quiet -dumpbase parser.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/ea708c7824d36062-parser.o -g -gdwarf-4 -O0 -Wall -Wextra ...\n12.247  as               1030607 1030605   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I src -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/ea708c7824d36062-parser.o /tmp/ccEWQd1J.s\n12.288  powerpc64le-lin  1030608 1030601   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/libtree-sitter-c.a /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/ea708c7824d36062-parser.o\n12.290  powerpc64le-lin  1030609 1030601   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/tree-sitter-c-d63c92033d1f4463/out/libtree-sitter-c.a\n12.295  rustc            1030611 1030478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_c --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ead31c8f41a81440 ...\n15.465  16               1030618 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n15.476  frpc             1030618 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n15.748  cross            1030625 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.749  rustc            1030628 1030625   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.756  rustc            1030628 1030625   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.770  rustc            1030640 1030625   0 /home/xmoe/.cargo/bin/rustc -vV\n15.777  rustc            1030640 1030625   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.788  cargo            1030650 1030625   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.795  cargo            1030650 1030625   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.808  rustc            1030659 1030650   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.820  rustc            1030661 1030650   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.835  rustc            1030665 1030650   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.867  rustc            1030669 1030625   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.874  rustc            1030669 1030625   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.888  docker           1030681 1030625   0 /usr/bin/docker --help\n15.903  docker           1030694 1030625   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.917  runc             1030705 1599     0 /usr/bin/runc --version\n15.920  cross            1030711 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n15.920  docker-init      1030713 1599     0 /usr/bin/docker-init --version\n15.922  docker           1030716 1030625   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.922  rustc            1030715 1030711   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.928  rustc            1030715 1030711   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.935  runc             1030735 1599     0 /usr/bin/runc --version\n15.939  docker-init      1030744 1599     0 /usr/bin/docker-init --version\n15.942  rustc            1030748 1030711   0 /home/xmoe/.cargo/bin/rustc -vV\n15.948  rustc            1030748 1030711   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.959  cargo            1030758 1030711   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.966  cargo            1030758 1030711   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.966  rustup           1030767 1030625   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.972  rustup           1030776 1030625   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.979  rustc            1030785 1030758   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.991  rustc            1030787 1030758   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.002  rustup           1030791 1030625   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.006  rustc            1030800 1030758   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.028  rustc            1030804 1030711   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.031  uname            1030805 1030625   0 /usr/bin/uname -r\n16.035  rustc            1030804 1030711   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.049  docker           1030817 1030711   0 /usr/bin/docker --help\n16.052  docker           1030823 1030625   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.064  docker           1030839 1030711   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.078  runc             1030852 1599     0 /usr/bin/runc --version\n16.081  docker-init      1030858 1599     0 /usr/bin/docker-init --version\n16.082  docker           1030859 1030711   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.096  runc             1030871 1599     0 /usr/bin/runc --version\n16.100  docker-init      1030877 1599     0 /usr/bin/docker-init --version\n16.125  rustup           1030878 1030711   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.133  rustup           1030887 1030711   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.154  systemd-sysctl   1030898 1030896   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9801767 --prefix=/net/ipv4/neigh/veth9801767 --prefix=/net/ipv6/conf/veth9801767 --prefix=/net/ipv6/neigh/veth9801767\n16.156  systemd-sysctl   1030899 1030897   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdcc2df3 --prefix=/net/ipv4/neigh/vethdcc2df3 --prefix=/net/ipv6/conf/vethdcc2df3 --prefix=/net/ipv6/neigh/vethdcc2df3\n16.167  rustup           1030920 1030711   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.170  containerd-shim  1030927 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35fb4ca start\n16.173  containerd-shim  1030947 1030927   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35fb4ca -address /var/run/docker/containerd/containerd.sock\n16.177  runc             1030956 1030947   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35 bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35fb4ca\n16.184  exe              1030963 1030956   0 /proc/self/exe init\n16.199  uname            1030965 1030711   0 /usr/bin/uname -r\n16.220  docker           1030973 1030711   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.226  exe              1030979 1030956   0 /proc/1599/exe -exec-root=/var/run/docker bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35fb4ca d7da31e8f8e1\n16.253  exe              1030996 1599     0 /proc/self/exe /var/run/docker/netns/0cbd66f26903 all false\n16.260  systemd-sysctl   1031002 1030918   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8013506 --prefix=/net/ipv4/neigh/veth8013506 --prefix=/net/ipv6/conf/veth8013506 --prefix=/net/ipv6/neigh/veth8013506\n16.260  systemd-sysctl   1031003 1030921   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3aeaf22 --prefix=/net/ipv4/neigh/veth3aeaf22 --prefix=/net/ipv6/conf/veth3aeaf22 --prefix=/net/ipv6/neigh/veth3aeaf22\n16.279  containerd-shim  1031010 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e66d7f start\n16.283  containerd-shim  1031020 1031010   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e66d7f -address /var/run/docker/containerd/containerd.sock\n16.286  runc             1031029 1031020   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e 78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e66d7f\n16.293  exe              1031036 1031029   0 /proc/self/exe init\n16.316  runc             1031047 1030947   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35 --log-format json --systemd-cgroup start bd3d4b617cc0661003dc489f8ffc47f819b5b3757d0cd60c02c72acbf35fb4ca\n16.322  sh               1030967 1030947   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.323  cargo            1031053 1030967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.335  exe              1031054 1031029   0 /proc/1599/exe -exec-root=/var/run/docker 78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e66d7f d7da31e8f8e1\n16.337  cargo-native-tr  1031053 1030967   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.341  cargo            1031060 1031053   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.355  rustc            1031063 1031060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.361  exe              1031064 1599     0 /proc/self/exe /var/run/docker/netns/dd7df7f934f1 all false\n16.365  cross            1031071 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n16.366  rustc            1031074 1031071   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.368  rustc            1031075 1031060   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.372  rustc            1031074 1031071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.387  rustc            1031103 1031071   0 /home/xmoe/.cargo/bin/rustc -vV\n16.393  rustc            1031103 1031071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.403  execsnoop        1031113 1031053   0 /usr/local/bin/execsnoop -t\n16.404  python3          1031113 1031053   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.404  cargo            1031116 1031071   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.411  cargo            1031116 1031071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.420  runc             1031127 1031020   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e --log-format json --systemd-cgroup start 78e833767866f70b3464c3663209a69bda36a65c771f95dc786950a034e66d7f\n16.425  sh               1031040 1031020   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.426  rustc            1031133 1031116   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.427  cargo            1031134 1031040   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.437  rustc            1031136 1031116   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.440  cargo-native-tr  1031134 1031040   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.444  cargo            1031137 1031134   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.451  rustc            1031141 1031116   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.457  rustc            1031142 1031137   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.467  rustc            1031147 1031137   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.470  rustc            1031148 1031071   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.475  rustc            1031148 1031071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.485  docker           1031163 1031071   0 /usr/bin/docker --help\n16.489  execsnoop        1031169 1031134   0 /usr/local/bin/execsnoop -t\n16.489  python3          1031169 1031134   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.497  docker           1031177 1031071   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.508  runc             1031185 1599     0 /usr/bin/runc --version\n16.510  docker-init      1031191 1599     0 /usr/bin/docker-init --version\n16.511  docker           1031192 1031071   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.522  runc             1031203 1599     0 /usr/bin/runc --version\n16.526  docker-init      1031209 1599     0 /usr/bin/docker-init --version\n16.546  rustup           1031210 1031071   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.552  rustup           1031219 1031071   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.574  rustup           1031228 1031071   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.596  uname            1031237 1031071   0 /usr/bin/uname -r\n16.612  docker           1031238 1031071   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.663  systemd-sysctl   1031253 1030921   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0a0b46a --prefix=/net/ipv4/neigh/veth0a0b46a --prefix=/net/ipv6/conf/veth0a0b46a --prefix=/net/ipv6/neigh/veth0a0b46a\n16.663  systemd-sysctl   1031252 1030918   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc6ab637 --prefix=/net/ipv4/neigh/vethc6ab637 --prefix=/net/ipv6/conf/vethc6ab637 --prefix=/net/ipv6/neigh/vethc6ab637\n16.678  containerd-shim  1031254 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda438467941 start\n16.681  containerd-shim  1031260 1031254   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda438467941 -address /var/run/docker/containerd/containerd.sock\n16.684  runc             1031270 1031260   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda4384 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda4384 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda4384 cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda438467941\n16.689  exe              1031278 1031270   0 /proc/self/exe init\n16.724  exe              1031286 1031270   0 /proc/1599/exe -exec-root=/var/run/docker cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda438467941 d7da31e8f8e1\n16.744  exe              1031295 1599     0 /proc/self/exe /var/run/docker/netns/1052dc6bb427 all false\n16.788  runc             1031314 1031260   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda4384 --log-format json --systemd-cgroup start cbe1aa9602a36abb5cf03ec6cb105a235354610ed8d1cfbfa131eda438467941\n16.793  sh               1031280 1031260   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.794  cargo            1031320 1031280   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n16.803  cargo-native-tr  1031320 1031280   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n16.806  cargo            1031321 1031320   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.816  rustc            1031322 1031321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.826  rustc            1031324 1031321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.847  execsnoop        1031328 1031320   0 /usr/local/bin/execsnoop -t\n16.848  python3          1031328 1031320   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.253  runc             1031331 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1639587015 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n18.258  exe              1031339 1031331   0 /proc/self/exe init\n18.286  etcdctl          1031341 1031331   0 /usr/local/bin/etcdctl endpoint health\n18.324  cargo            1031356 1031134   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n18.336  rustc            1031357 1031356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.356  rustc            1031367 1031356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.152/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n18.357  rustc            1031365 1031356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=3b393852d2f0042a ...\n18.357  rustc            1031368 1031356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.79/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=5b7572f701307434 ...\n18.357  rustc            1031369 1031356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"rustc-dep-of-std\")) -C metadata=44346b50c4e9393e ...\n"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1029411,
      "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
      "pid": 1029411,
      "ppid": 1029317,
      "root_cargo_pid": 1029317,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1029594,
      "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build-script-build",
      "pid": 1029594,
      "ppid": 1029317,
      "root_cargo_pid": 1029317,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-E",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/138872970189759799detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1029594,
      "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 1029595,
      "ppid": 1029594,
      "root_cargo_pid": 1029317,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/138872970189759799detect_compiler_family.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1029594,
      "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 1029596,
      "ppid": 1029595,
      "root_cargo_pid": 1029317,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1029594,
      "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 1029597,
      "ppid": 1029594,
      "root_cargo_pid": 1029317,
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
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o",
        "-c",
        "src/parser.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1029594,
      "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 1029598,
      "ppid": 1029594,
      "root_cargo_pid": 1029317,
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
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "-Wextra",
        "-std=c11",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 1029594,
      "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 1029599,
      "ppid": 1029598,
      "root_cargo_pid": 1029317,
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
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o",
        "/tmp/ccmw6jAz.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1029594,
      "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 1029618,
      "ppid": 1029598,
      "root_cargo_pid": 1029317,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "cqD",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/libtree-sitter-c.a",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/ea708c7824d36062-parser.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1029594,
      "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 1029619,
      "ppid": 1029594,
      "root_cargo_pid": 1029317,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "sD",
        "/target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-0a554a65564179f1/out/libtree-sitter-c.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1029594,
      "build_script_target_dir": "tree-sitter-c-a5737ebafafa61cc",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 1029620,
      "ppid": 1029594,
      "root_cargo_pid": 1029317,
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
      "crate": "tree-sitter-c",
      "cwd": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "event_id": "bsrun:c65d634499ab6877:f3e62e358bbf8c4b:9ce2aa4c2c50ab9d",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
      "out_dir": "/target/debug/build/tree-sitter-c-a5737ebafafa61cc/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
      "success": true,
      "target": null,
      "version": "0.23.4",
      "_owner": {
        "crate": "tree-sitter-c",
        "version": "0.23.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4#tree-sitter-c@0.23.4",
        "manifest_dir": "/tmp/crate-build-aarch64-jdag6whl/src/tree-sitter-c-0.23.4",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 4017,
    "crate": "tree-sitter-c",
    "version": "0.23.4",
    "crate_id": "452052",
    "version_id": "1375923",
    "downloads": 2131650,
    "cumulative_downloads": 109772430364,
    "cumulative_share_of_global": 0.41041377552710107,
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
