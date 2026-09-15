# `serde_json` `1.0.140`

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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
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
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39",
    "/target/debug/build/serde_json-f663e98440021490",
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
      "directory": "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51400-1783992784105682433.map",
  "pid": 51400,
  "ppid": 51263,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51400-1783992784105682433.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "workspace_root": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#automod@1.0.14",
      "name": "automod",
      "version": "1.0.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/automod-1.0.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/automod-1.0.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.16",
      "name": "cc",
      "version": "1.2.16",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.16/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#dissimilar@1.0.9",
      "name": "dissimilar",
      "version": "1.0.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dissimilar-1.0.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dissimilar-1.0.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.2",
      "name": "equivalent",
      "version": "1.0.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.2",
      "name": "glob",
      "version": "0.3.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.15.2",
      "name": "hashbrown",
      "version": "0.15.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.15.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.15.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.7.1",
      "name": "indexmap",
      "version": "2.7.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.7.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.7.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#indoc@2.0.5",
      "name": "indoc",
      "version": "2.0.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indoc-2.0.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indoc-2.0.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
      "name": "itoa",
      "version": "1.0.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.170",
      "name": "libc",
      "version": "0.2.170",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.170/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.170"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
      "name": "memchr",
      "version": "2.7.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.94",
      "name": "proc-macro2",
      "version": "1.0.94",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#psm@0.1.25",
      "name": "psm",
      "version": "0.1.25",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/psm-0.1.25/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/psm-0.1.25"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.39",
      "name": "quote",
      "version": "1.0.39",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.39/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.39"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ref-cast@1.0.24",
      "name": "ref-cast",
      "version": "1.0.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-1.0.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-1.0.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ref-cast-impl@1.0.24",
      "name": "ref-cast-impl",
      "version": "1.0.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-impl-1.0.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-impl-1.0.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.19",
      "name": "rustversion",
      "version": "1.0.19",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.19/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.19",
      "name": "ryu",
      "version": "1.0.19",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
      "name": "serde",
      "version": "1.0.218",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_bytes@0.11.16",
      "name": "serde_bytes",
      "version": "0.11.16",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_bytes-0.11.16/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_bytes-0.11.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.218",
      "name": "serde_derive",
      "version": "1.0.218",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.218/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.218"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.139",
      "name": "serde_json",
      "version": "1.0.139",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.139/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.139"
    },
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
      "name": "serde_json",
      "version": "1.0.140",
      "manifest_path": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_spanned@0.6.8",
      "name": "serde_spanned",
      "version": "0.6.8",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-0.6.8/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-0.6.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_stacker@0.1.12",
      "name": "serde_stacker",
      "version": "0.1.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_stacker-0.1.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_stacker-0.1.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
      "name": "shlex",
      "version": "1.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#stacker@0.1.19",
      "name": "stacker",
      "version": "0.1.19",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stacker-0.1.19/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stacker-0.1.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.99",
      "name": "syn",
      "version": "2.0.99",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.99/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.99"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-triple@0.1.4",
      "name": "target-triple",
      "version": "0.1.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-0.1.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-0.1.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
      "name": "termcolor",
      "version": "1.4.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml@0.8.20",
      "name": "toml",
      "version": "0.8.20",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.8.20/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.8.20"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@0.6.8",
      "name": "toml_datetime",
      "version": "0.6.8",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.6.8/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.6.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_edit@0.22.24",
      "name": "toml_edit",
      "version": "0.22.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.22.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.22.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.103",
      "name": "trybuild",
      "version": "1.0.103",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.103/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.103"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.17",
      "name": "unicode-ident",
      "version": "1.0.17",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.17/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.17"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.9",
      "name": "winapi-util",
      "version": "0.1.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
      "name": "windows-sys",
      "version": "0.59.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0"
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
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@0.7.3",
      "name": "winnow",
      "version": "0.7.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.7.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.7.3"
    }
  ],
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "exit_code": 0,
  "kind": "exec",
  "pid": 51400,
  "ppid": 51263,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "used:cc:b9f1db8b570e5bf6:124c53a02476624e:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
  "pid": 51400,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "used:cc:b9f1db8b570e5bf6:d034368ae7556ed4:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
  "pid": 51400,
  "sha256": "570a94b503a477ebd3545da4d169716edc8bc5411921f7c9756a4224df54d908",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "used:cc:b9f1db8b570e5bf6:d8282c42341a01de:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
  "pid": 51400,
  "sha256": "8702743256d940c3aa508b2ecd830251cb2d8d6941ddf7a48eba1000dd0f6e5f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "used:cc:b9f1db8b570e5bf6:df61e11a738d6b36:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
  "pid": 51400,
  "sha256": "1cbeda0d482ebec946209c09c02e2ee9ea6530cf47c1c0f2db005eab7aeace49",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "used:cc:b9f1db8b570e5bf6:7418c6a869bf20bd:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
  "pid": 51400,
  "sha256": "30a250e4c725df1e0c01195e23cb383a6a11124391099a178b20d9a7ce738094",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "used:cc:b9f1db8b570e5bf6:f1284966aa4a12db:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
  "pid": 51400,
  "sha256": "65f01bdd545f06bb22692b08a5bb2b760bedbdf548b6fb2edab9c82ca7ebb1b3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "used:cc:b9f1db8b570e5bf6:fdf3c311bc58bdb7:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
  "pid": 51400,
  "sha256": "d823d9ff3b33d9402e459193d3b1554744c53c64fccb5984b5dec57d58948294",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "used:cc:b9f1db8b570e5bf6:57e72c7f5e9664f0:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
  "pid": 51400,
  "sha256": "c7e40648779a1725fde38708952d07cb6c92d3195f16771e240e986c9355409c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "used:cc:b9f1db8b570e5bf6:f2902fe3392a3a8d:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
  "pid": 51400,
  "sha256": "250660162e4e638b49f8ee1ed921b3d811bbb533927197dc3389041e0e901abb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "used:cc:b9f1db8b570e5bf6:9e895b8440a09458:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
  "pid": 51400,
  "sha256": "c3786f633cd8e55f38df7c01163d7db848421d8faf0b56756f3e77e4a8b7dd9f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "used:cc:b9f1db8b570e5bf6:8075f17b0b870db0:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
  "pid": 51400,
  "sha256": "7fcb4eb2fb437bc0bc537b6c93b1935273d9bae18d1333b82878b293714891e7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
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
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "context_path": "/tmp/native-trace-50172-1783992780094/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-50172-1783992780094/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 51400,
  "ppid": 51263,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39",
    "/target/debug/build/serde_json-f663e98440021490",
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
      "directory": "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51400-1783992784105682433.map",
  "pid": 51400,
  "ppid": 51263,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51400-1783992784105682433.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "exit_code": 0,
  "kind": "exec",
  "pid": 51636,
  "ppid": 51258,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde",
    "version": "1.0.218",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.218",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "event_id": "used:cc:bc511c808a7c37c7:4ec85ebe8241ec9d:3bd91b3119723b6e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
  "path": "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
  "pid": 51636,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde",
    "version": "1.0.218",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.218",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "event_id": "used:cc:bc511c808a7c37c7:ef0e413b02d274b8:3bd91b3119723b6e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
  "path": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
  "pid": 51636,
  "sha256": "b112d573278ac5b3ac86053b07f90f1f07612cee278867c6c3bba2efe9da4393",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde",
    "version": "1.0.218",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.218",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "event_id": "used:cc:bc511c808a7c37c7:9873dfd73ce6c9e9:3bd91b3119723b6e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
  "path": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
  "pid": 51636,
  "sha256": "a485ce845d1b83556f32ad7510c2900c44192736b8c0695d7ee72935eb16077f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde",
    "version": "1.0.218",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
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
  "output": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde",
    "version": "1.0.218",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "cargo_pkg_name": "serde",
  "cargo_pkg_version": "1.0.218",
  "context_path": "/tmp/native-trace-50172-1783992780094/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-50172-1783992780094/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 51636,
  "ppid": 51258,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "_owner": {
    "crate": "serde",
    "version": "1.0.218",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ",
    "/target/debug/build/serde-fc0ba381ae66b83b",
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
      "directory": "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ",
      "kind": "object",
      "path": "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde-fc0ba381ae66b83b",
      "kind": "object",
      "path": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde-fc0ba381ae66b83b",
      "kind": "object",
      "path": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51636-1783992784399263723.map",
  "pid": 51636,
  "ppid": 51258,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51636-1783992784399263723.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "serde",
    "version": "1.0.218",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
    "source": "cargo_manifest_dir"
  }
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

#### Record 25

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 765,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 767,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "tainerd/containerd.sock -publish-binary /usr/bin/containerd -id 86bc0bef27803e7498cb120c93515d2273628c95e3b3a4c8553dfb51501e657c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86bc0bef27803e7498cb120c93515d2273628c95e3b3a4c8553dfb51501 delete\n13.323  runc             54186  54173    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86bc0bef27803e7498cb120c93515d2273628c95e3b3a4c8553dfb51501e657 --log-format json delete --force 86bc0bef27803e7498cb120c93515d2273628c95e3b3a4c8553dfb51501e657c\n13.344  etcdctl          54174  54162    0 /usr/local/bin/etcdctl endpoint health\n13.364  sh               54203  54200    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth697c247\n13.366  ethtool          54204  54203    0 /usr/sbin/ethtool -i veth697c247\n13.366  sed              54205  54203    0 /usr/bin/sed -n s/^driver: //p\n13.373  systemd-sysctl   54208  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth697c247 --prefix=/net/ipv4/neigh/veth697c247 --prefix=/net/ipv6/conf/veth697c247 --prefix=/net/ipv6/neigh/veth697c247\n14.030  runc             54210  46371    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 --log-format json --systemd-cgroup kill --all e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78 9\n14.049  runc             54216  46371    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 --log-format json --systemd-cgroup delete e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78\n14.073  sh               54222  2147557   0 /bin/sh -c which ps\n14.075  which            54222  2147557   0 /usr/bin/which ps\n14.077  sh               54223  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.079  ps               54223  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.116  sh               54224  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n14.118  cpuUsage.sh      54224  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n14.120  sed              54225  54224    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.123  cat              54226  54224    0 /usr/bin/cat /proc/2240539/stat\n14.124  cat              54227  54224    0 /usr/bin/cat /proc/4193716/stat\n14.126  sleep            54228  54224    0 /usr/bin/sleep 1\n14.219  16               54231  1        0 /proc/self/fd/16 --deserialize 145 --log-level info --log-target journal-or-kmsg\n14.222  16               54232  1        0 /proc/self/fd/16 --deserialize 157 --log-level info --log-target journal-or-kmsg\n14.283  containerd-shim  54234  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 delete\n14.286  runc             54241  54234    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e7 --log-format json delete --force e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78\n14.320  systemd-sysctl   54246  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth185aa5a --prefix=/net/ipv4/neigh/veth185aa5a --prefix=/net/ipv6/conf/veth185aa5a --prefix=/net/ipv6/neigh/veth185aa5a\n14.376  drkonqi-coredum  54232  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 890-54230-0\n14.381  systemd-coredum  54231  1        0 /usr/lib/systemd/systemd-coredump\n14.913  9                54257  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n14.919  abrt-server      54258  1118     0 /usr/bin/abrt-server -s\n14.931  drkonqi-coredum  54257  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n14.948  abrt-handle-eve  54259  54258    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:33:18.647156-53364\n14.964  sh               54262  54259    0 /bin/sh -c abrt-action-save-package-data\\n\n14.966  abrt-action-sav  54262  54259    0 /usr/bin/abrt-action-save-package-data\n14.982  9                54265  4003047   0 /proc/self/fd/9 --deserialize 44 --log-level info --log-target auto\n14.986  plasma_waitforn  54265  4003047   0 /usr/bin/plasma_waitforname org.freedesktop.Notifications\n15.030  sh               54267  54259    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n15.032  cut              54269  54267    0 /usr/bin/cut -d: -f1\n15.032  cat              54270  54268    0 /usr/bin/cat uid\n15.033  getent           54268  54267    0 /usr/bin/getent passwd 1000\n15.035  lscpu            54271  54267    0 /usr/bin/lscpu\n15.053  sh               54272  54259    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n15.054  runlevel         54273  54272    0 /usr/bin/runlevel\n15.066  sh               54274  54259    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n15.067  grep             54275  54274    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n15.069  grep             54276  54274    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n15.071  grep             54277  54274    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n15.072  abrt-action-cor  54278  54274    0 /usr/libexec/abrt-action-coredump -x\n15.128  sed              54279  54224    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.131  cat              54280  54224    0 /usr/bin/cat /proc/2240539/stat\n15.134  cat              54282  54224    0 /usr/bin/cat /proc/4193716/stat\n15.140  abrt-action-gen  54284  54274    0 /usr/bin/abrt-action-generate-core-backtrace\n15.197  abrt-action-ana  54285  54274    0 /usr/bin/abrt-action-analyze-vulnerability\n15.199  eu-readelf       54287  54286    0 /usr/bin/eu-readelf -n coredump\n15.200  sed              54289  54286    0 /usr/bin/sed s/[^0-9]//g\n15.200  grep             54288  54286    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n15.203  gdb              54291  54290    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n15.220  iconv            54292  54291    0 /usr/bin/iconv -l\n15.325  abrt-action-ana  54301  54274    0 /usr/bin/abrt-action-analyze-c\n15.339  eu-unstrip       54302  54301    0 /usr/bin/eu-unstrip --core=./coredump -n\n15.359  abrt-action-lis  54303  54274    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n15.424  cat              54305  54304    0 /usr/bin/cat executable\n15.426  cat              54306  54304    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:33:18.647156-53364/uid\n15.428  journalctl       54307  54304    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n15.442  abrt-action-cor  54308  54274    0 /usr/libexec/abrt-action-coredump -r\n15.493  abrt-handle-eve  54309  54258    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.505  sh               54310  54309    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n15.506  dbus-send        54310  54309    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.508  sh               54311  54309    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n15.509  abrt-action-not  54312  54311    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.559  sh               54313  54312    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n15.560  reporter-system  54313  54312    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n16.942  runc             54316  46203    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 --log-format json --systemd-cgroup kill --all c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2 9\n16.951  16               54322  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n16.968  frpc             54322  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n16.970  runc             54327  46203    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 --log-format json --systemd-cgroup delete c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2\n17.002  cross            54333  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.002  rustc            54336  54333    0 \n17.005  rustc            54336  54333    0 /home/xmoe/.cargo/bin/rustc --print target-list /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.019  rustc            54348  54333    0 /home/xmoe/.cargo/bin/rustc -vV\n17.026  rustc            54348  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.038  cargo            54358  54333    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.044  cargo            54358  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.057  rustc            54367  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.069  rustc            54369  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.084  rustc            54373  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.135  rustc            54377  54333    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.141  rustc            54377  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.156  docker           54389  54333    0 /usr/bin/docker --help\n17.162  containerd-shim  54395  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 delete\n17.166  runc             54407  54395    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f --log-format json delete --force c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2\n17.172  docker           54413  54333    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.186  runc             54423  1599     0 /usr/bin/runc --version\n17.190  docker-init      54429  1599     0 /usr/bin/docker-init --version\n17.191  docker           54430  54333    0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.207  runc             54442  1599     0 /usr/bin/runc --version\n17.208  sh               54443  54200    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth7a6f9c6\n17.209  ethtool          54449  54443    0 /usr/sbin/ethtool -i veth7a6f9c6\n17.210  sed              54450  54443    0 /usr/bin/sed -n s/^driver: //p\n17.212  docker-init      54452  1599     0 /usr/bin/docker-init --version\n17.218  systemd-sysctl   54458  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7a6f9c6 --prefix=/net/ipv4/neigh/veth7a6f9c6 --prefix=/net/ipv6/conf/veth7a6f9c6 --prefix=/net/ipv6/neigh/veth7a6f9c6\n17.243  rustup           54459  54333    0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.251  rustup           54468  54333    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.281  rustup           54477  54333    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.311  uname            54486  54333    0 /usr/bin/uname -r\n17.334  docker           54487  54333    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.376  systemd-sysctl   54499  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6023135 --prefix=/net/ipv4/neigh/veth6023135 --prefix=/net/ipv6/conf/veth6023135 --prefix=/net/ipv6/neigh/veth6023135\n17.376  systemd-sysctl   54500  54247    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb507d9f --prefix=/net/ipv4/neigh/vethb507d9f --prefix=/net/ipv6/conf/vethb507d9f --prefix=/net/ipv6/neigh/vethb507d9f\n17.393  containerd-shim  54527  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 start\n17.399  containerd-shim  54537  54527    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 -address /var/run/docker/containerd/containerd.sock\n17.402  cross            54542  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n17.403  rustc            54545  54542    0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.405  runc             54551  54537    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0\n17.413  exe              54566  54551    0 /proc/self/exe init\n17.433  rustc            54545  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.448  rustc            54579  54542    0 /home/xmoe/.cargo/bin/rustc -vV\n17.455  exe              54588  54551    0 /proc/1599/exe -exec-root=/var/run/docker 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 d7da31e8f8e1\n17.479  rustc            54579  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.480  exe              54596  1599     0 /proc/self/exe /var/run/docker/netns/89f6772925ee all false\n17.492  cargo            54606  54542    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.511  runc             54622  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup kill --all 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a 9\n17.520  runc             54628  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup delete 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.525  cargo            54606  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.536  runc             54634  54537    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --log-format json --systemd-cgroup start 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0\n17.540  rustc            54640  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.543  sh               54570  54537    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.544  cargo            54641  54570    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.553  rustc            54643  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.559  cargo-native-tr  54641  54570    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.564  cargo            54645  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.569  rustc            54648  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.578  rustc            54651  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.590  rustc            54654  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.609  rustc            54658  54542    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.631  rustc            54658  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.643  docker           54670  54542    0 /usr/bin/docker --help\n17.647  execsnoop        54676  54641    0 /usr/local/bin/execsnoop -t\n17.648  python3          54676  54641    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.656  docker           54687  54542    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.666  runc             54696  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup kill --all a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 9\n17.667  runc             54697  1599     0 /usr/bin/runc --version\n17.669  docker-init      54708  1599     0 /usr/bin/docker-init --version\n17.670  docker           54709  54542    0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.673  runc             54715  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup delete a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.682  runc             54726  1599     0 /usr/bin/runc --version\n17.685  docker-init      54732  1599     0 /usr/bin/docker-init --version\n17.705  rustup           54733  54542    0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.719  containerd-shim  54743  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b delete\n17.721  runc             54750  54743    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9 --log-format json delete --force 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.729  rustup           54755  54542    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.752  rustup           54764  54542    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.753  systemd-sysctl   54765  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe425dec --prefix=/net/ipv4/neigh/vethe425dec --prefix=/net/ipv6/conf/vethe425dec --prefix=/net/ipv6/neigh/vethe425dec\n17.776  uname            54774  54542    0 /usr/bin/uname -r\n17.794  docker           54775  54542    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.830  systemd-sysctl   54789  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth76e10a3 --prefix=/net/ipv4/neigh/veth76e10a3 --prefix=/net/ipv6/conf/veth76e10a3 --prefix=/net/ipv6/neigh/veth76e10a3\n17.830  systemd-sysctl   54788  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf2069ec --prefix=/net/ipv4/neigh/vethf2069ec --prefix=/net/ipv6/conf/vethf2069ec --prefix=/net/ipv6/neigh/vethf2069ec\n17.845  containerd-shim  54791  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 start\n17.848  containerd-shim  54798  54791    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 -address /var/run/docker/containerd/containerd.sock\n17.852  runc             54808  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.853  containerd-shim  54811  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 delete\n17.855  runc             54820  54811    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f495792 --log-format json delete --force a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.857  exe              54827  54808    0 /proc/self/exe init\n17.892  systemd-sysctl   54832  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7f2e47d --prefix=/net/ipv4/neigh/veth7f2e47d --prefix=/net/ipv6/conf/veth7f2e47d --prefix=/net/ipv6/neigh/veth7f2e47d\n17.907  exe              54838  54808    0 /proc/1599/exe -exec-root=/var/run/docker 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 d7da31e8f8e1\n17.927  exe              54846  1599     0 /proc/self/exe /var/run/docker/netns/3e401da5d4b2 all false\n17.986  runc             54864  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup start 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.992  sh               54831  54798    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.993  cargo            54870  54831    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n18.003  cargo-native-tr  54870  54831    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n18.006  cargo            54871  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.016  rustc            54872  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.028  rustc            54874  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.037  runc             54878  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup kill --all bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 9\n18.054  runc             54885  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup delete bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n18.066  execsnoop        54891  54870    0 /usr/local/bin/execsnoop -t\n18.067  python3          54891  54870    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.080  runc             54894  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup kill --all a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 9\n18.098  runc             54901  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup delete a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.275  containerd-shim  54907  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b delete\n18.277  runc             54914  54907    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf788 --log-format json delete --force bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n18.314  systemd-sysctl   54919  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfb8276c --prefix=/net/ipv4/neigh/vethfb8276c --prefix=/net/ipv6/conf/vethfb8276c --prefix=/net/ipv6/neigh/vethfb8276c\n18.322  containerd-shim  54921  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 delete\n18.324  runc             54928  54921    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f --log-format json delete --force a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.368  systemd-sysctl   54933  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth651aca6 --prefix=/net/ipv4/neigh/veth651aca6 --prefix=/net/ipv6/conf/veth651aca6 --prefix=/net/ipv6/neigh/veth651aca6\n18.434  runc             54934  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup kill --all f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 9\n18.451  runc             54940  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup delete f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.631  containerd-shim  54946  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 delete\n18.634  runc             54953  54946    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da9 --log-format json delete --force f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.671  systemd-sysctl   54959  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd600a16 --prefix=/net/ipv4/neigh/vethd600a16 --prefix=/net/ipv6/conf/vethd600a16 --prefix=/net/ipv6/neigh/vethd600a16\n18.739  runc             54961  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup kill --all 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 9\n18.746  runc             54967  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup delete 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.926  containerd-shim  54974  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d delete\n18.928  runc             54981  54974    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d9863 --log-format json delete --force 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.963  systemd-sysctl   54986  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b8f709 --prefix=/net/ipv4/neigh/veth5b8f709 --prefix=/net/ipv6/conf/veth5b8f709 --prefix=/net/ipv6/neigh/veth5b8f709\n19.074  sh               54987  2147557   0 /bin/sh -c which ps\n19.075  which            54987  2147557   0 /usr/bin/which ps\n19.077  sh               54988  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.078  ps               54988  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.103  sh               54989  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n19.104  cpuUsage.sh      54989  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n19.105  sed              54990  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.107  cat              54991  54989    0 /usr/bin/cat /proc/2240539/stat\n19.108  cat              54992  54989    0 /usr/bin/cat /proc/4193716/stat\n19.109  sleep            54993  54989    0 /usr/bin/sleep 1\n19.502  cargo            54994  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n19.515  rustc            54995  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.544  rustc            55001  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.585  cc               55024  55001    0 /tmp/native-trace-54641-1783992801298/shims/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.585  cc               55025  55024    0 /usr/bin/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.588  collect2         55026  55025    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.589  ld.lld           55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781 ...\n19.590  rust-lld         55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.628  build-script-bu  55045  54994    0 /target/debug/build/valuable-0ca3a52e87f47781/build-script-build\n19.632  rustc            55047  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name valuable --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.912  cargo            55059  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n19.925  rustc            55070  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.950  rustc            55113  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.950  rustc            55111  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba1b82e103e0280b ...\n20.049  cc               55188  55113    0 /tmp/native-trace-54870-1783992801742/shims/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n20.050  cc               55189  55188    0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n20.054  collect2         55190  55189    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.055  ld.lld           55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde ...\n20.056  rust-lld         55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.111  sed              55209  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.111  build-script-bu  55210  55059    0 /target/debug/build/proc-macro2-46239aad0aaf2dde/build-script-build\n20.113  cat              55211  54989    0 /usr/bin/cat /proc/2240539/stat\n20.113  rustc            55212  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n20.114  cat              55214  54989    0 /usr/bin/cat /proc/4193716/stat\n20.123  rustc            55217  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-1a2ad12dc9160ce7/out/probe build/probe.rs --target aarch64-unknown-linux-gnu\n20.150  rustc            55222  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.715  cross            55331  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.716  rustc            55334  55331    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.737  rustc            55334  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.749  rustc            55346  55331    0 /home/xmoe/.cargo/bin/rustc -vV\n20.770  rustc            55346  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.780  cargo            55356  55331    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.801  cargo            55356  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.812  rustc            55366  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.814  git              55365  2235138   0 /usr/bin/git config --get commit.template\n20.821  rustc            55368  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.829  git              55369  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n20.832  rustc            55373  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.845  git              55374  2235138   0 /usr/bin/git status -z -uall\n20.857  rustc            55379  55331    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.860  git              55378  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n20.879  rustc            55379  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.890  docker           55391  55331    0 /usr/bin/docker --help\n20.902  docker           55402  55331    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.914  runc             55412  1599     0 /usr/bin/runc --version\n20.917  docker-init      55418  1599     0 /usr/bin/docker-init --version\n20.918  docker           55419  55331    0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.929  runc             55430  1599     0 /usr/bin/runc --version\n20.932  docker-init      55436  1599     0 /usr/bin/docker-init --version\n20.953  rustup           55440  55331    0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.974  rustup           55449  55331    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.995  rustup           55458  55331    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n21.019  uname            55467  55331    0 /usr/bin/uname -r\n21.034  docker           55468  55331    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n21.070  systemd-sysctl   55483  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8170368 --prefix=/net/ipv4/neigh/veth8170368 --prefix=/net/ipv6/conf/veth8170368 --prefix=/net/ipv6/neigh/veth8170368\n21.070  systemd-sysctl   55482  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth81dd9a9 --prefix=/net/ipv4/neigh/veth81dd9a9 --prefix=/net/ipv6/conf/veth81dd9a9 --prefix=/net/ipv6/neigh/veth81dd9a9\n21.084  containerd-shim  55484  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 start\n21.087  containerd-shim  55491  55484    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 -address /var/run/docker/containerd/containerd.sock\n21.091  runc             55501  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n21.095  exe              55509  55501    0 /proc/self/exe init\n21.113  cross            55513  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n21.115  rustc            55520  55513    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.119  rustc            55520  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.129  exe              55532  55501    0 /proc/1599/exe -exec-root=/var/run/docker 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 d7da31e8f8e1\n21.131  rustc            55539  55513    0 /home/xmoe/.cargo/bin/rustc -vV\n21.135  rustc            55539  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.141  cross            55549  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n21.142  rustc            55552  55549    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.145  cargo            55561  55513    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.146  cross            55564  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n21.147  rustc            55567  55564    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.148  exe              55576  1599     0 /proc/self/exe /var/run/docker/netns/8b628a44607d all false\n21.150  cargo            55561  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.152  rustc            55567  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.161  rustc            55596  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.164  rustc            55597  55564    0 /home/xmoe/.cargo/bin/rustc -vV\n21.168  rustc            55552  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.169  rustc            55597  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.170  rustc            55607  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.177  cargo            55614  55564    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.179  rustc            55616  55549    0 /home/xmoe/.cargo/bin/rustc -vV\n21.180  rustc            55625  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.182  cargo            55614  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.193  rustc            55637  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.195  runc             55639  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup start 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n21.200  sh               55511  55491    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n21.201  cargo            55646  55511    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n21.203  rustc            55647  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.206  rustc            55616  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.213  cargo-native-tr  55646  55511    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n21.214  cargo            55652  55549    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.215  rustc            55653  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.217  cargo            55654  55646    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n21.227  rustc            55666  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.236  cargo            55652  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.239  rustc            55668  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.247  rustc            55670  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.256  rustc            55674  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.268  rustc            55678  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.304  git              55683  2235138   0 /usr/bin/git worktree list --porcelain\n21.342  cross            55684  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.343  rustc            55687  55684    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.348  rustc            55687  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.359  runc             55701  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup kill --all 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 9\n21.359  rustc            55700  55684    0 /home/xmoe/.cargo/bin/rustc -vV\n21.364  rustc            55700  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.373  cargo            55716  55684    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.376  runc             55725  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup delete 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.378  cargo            55716  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.388  rustc            55731  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.397  rustc            55733  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.420  rustc            55737  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n"
}
```

#### Record 26

```json
{
  "argv": [
    "/target/debug/build/serde_json-f663e98440021490/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 51536,
  "build_script_target_dir": "serde_json-f663e98440021490",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/serde_json-f663e98440021490/build-script-build",
  "pid": 51536,
  "ppid": 51169,
  "root_cargo_pid": 51169,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "_build_script_out_dir": "/target/debug/build/serde_json-f663e98440021490/out"
}
```

#### Record 27

```json
{
  "argv": [
    "/target/debug/build/serde-fc0ba381ae66b83b/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 51839,
  "build_script_target_dir": "serde-fc0ba381ae66b83b",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/serde-fc0ba381ae66b83b/build-script-build",
  "pid": 51839,
  "ppid": 51169,
  "root_cargo_pid": 51169,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "serde",
    "version": "1.0.218",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "_build_script_out_dir": "/target/debug/build/serde-fc0ba381ae66b83b/out"
}
```

#### Record 28

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 51839,
  "build_script_target_dir": "serde-fc0ba381ae66b83b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 51843,
  "ppid": 51839,
  "root_cargo_pid": 51169,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "serde",
    "version": "1.0.218",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "_build_script_out_dir": "/target/debug/build/serde-fc0ba381ae66b83b/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 29

```json
{
  "crate": "serde_json",
  "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "event_id": "bsrun:c42a269c07c36b4f:b53fe9c00a356d6f:135b23063d020806",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/serde_json-f663e98440021490/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
  "out_dir": "/target/debug/build/serde_json-f663e98440021490/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
  "success": true,
  "target": null,
  "version": "1.0.140",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
    "source": "cwd_prefix"
  }
}
```

#### Record 30

```json
{
  "crate": "serde",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "event_id": "bsrun:43533528a723ce4b:574517cea65d8a5b:423607d971467760",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/serde-fc0ba381ae66b83b/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "out_dir": "/target/debug/build/serde-fc0ba381ae66b83b/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
  "success": true,
  "target": null,
  "version": "1.0.218",
  "_owner": {
    "crate": "serde",
    "version": "1.0.218",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
    "source": "cwd_prefix"
  }
}
```

#### Record 31

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 51839,
  "build_script_target_dir": "serde-fc0ba381ae66b83b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 51843,
  "ppid": 51839,
  "root_cargo_pid": 51169,
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
  "time": "2026-07-14T01:33:25.598801+00:00",
  "crate": "serde_json",
  "version": "1.0.140",
  "architecture": "aarch64",
  "duration_seconds": 29.42770220292732,
  "trace_record_count": 30,
  "trace_owner_summary": {
    "owner_package_count": 48,
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
        "crate": "ref-cast-impl",
        "version": "1.0.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ref-cast-impl@1.0.24",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-impl-1.0.24",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-impl-1.0.24/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.218",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.218",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.218",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.218/Cargo.toml"
      },
      {
        "crate": "serde_stacker",
        "version": "0.1.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_stacker@0.1.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_stacker-0.1.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_stacker-0.1.12/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.17",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.17",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.17",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.17/Cargo.toml"
      },
      {
        "crate": "serde_bytes",
        "version": "0.11.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_bytes@0.11.16",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_bytes-0.11.16",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_bytes-0.11.16/Cargo.toml"
      },
      {
        "crate": "serde_spanned",
        "version": "0.6.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_spanned@0.6.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-0.6.8",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-0.6.8/Cargo.toml"
      },
      {
        "crate": "target-triple",
        "version": "0.1.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-triple@0.1.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-0.1.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-0.1.4/Cargo.toml"
      },
      {
        "crate": "toml_datetime",
        "version": "0.6.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@0.6.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.6.8",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.6.8/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.94",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.94",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94/Cargo.toml"
      },
      {
        "crate": "rustversion",
        "version": "1.0.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.19",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.19",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.19/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.139",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.139",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.139",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.139/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.59.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0/Cargo.toml"
      },
      {
        "crate": "toml_edit",
        "version": "0.22.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_edit@0.22.24",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.22.24",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.22.24/Cargo.toml"
      },
      {
        "crate": "winapi-util",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.9/Cargo.toml"
      },
      {
        "crate": "dissimilar",
        "version": "1.0.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#dissimilar@1.0.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dissimilar-1.0.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dissimilar-1.0.9/Cargo.toml"
      },
      {
        "crate": "equivalent",
        "version": "1.0.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2/Cargo.toml"
      },
      {
        "crate": "hashbrown",
        "version": "0.15.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.15.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.15.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.15.2/Cargo.toml"
      },
      {
        "crate": "trybuild",
        "version": "1.0.103",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.103",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.103",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.103/Cargo.toml"
      },
      {
        "crate": "ref-cast",
        "version": "1.0.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ref-cast@1.0.24",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-1.0.24",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-1.0.24/Cargo.toml"
      },
      {
        "crate": "termcolor",
        "version": "1.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1/Cargo.toml"
      },
      {
        "crate": "automod",
        "version": "1.0.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#automod@1.0.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/automod-1.0.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/automod-1.0.14/Cargo.toml"
      },
      {
        "crate": "indexmap",
        "version": "2.7.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.7.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.7.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.7.1/Cargo.toml"
      },
      {
        "crate": "stacker",
        "version": "0.1.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#stacker@0.1.19",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stacker-0.1.19",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stacker-0.1.19/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.218",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218/Cargo.toml"
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
        "version": "0.2.170",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.170",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.170",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.170/Cargo.toml"
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
        "version": "1.0.39",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.39",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.39",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.39/Cargo.toml"
      },
      {
        "crate": "winnow",
        "version": "0.7.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@0.7.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.7.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.7.3/Cargo.toml"
      },
      {
        "crate": "indoc",
        "version": "2.0.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#indoc@2.0.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indoc-2.0.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indoc-2.0.5/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "1.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml"
      },
      {
        "crate": "toml",
        "version": "0.8.20",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml@0.8.20",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.8.20",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.8.20/Cargo.toml"
      },
      {
        "crate": "glob",
        "version": "0.3.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2/Cargo.toml"
      },
      {
        "crate": "psm",
        "version": "0.1.25",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#psm@0.1.25",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/psm-0.1.25",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/psm-0.1.25/Cargo.toml"
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
        "version": "2.0.99",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.99",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.99",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.99/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.16",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.16",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.16/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "manifest_path": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140/Cargo.toml"
      }
    ],
    "attributed_event_count": 25,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "serde_json",
        "version": "1.0.140",
        "event_count": 17,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 11,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "serde",
        "version": "1.0.218",
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
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "workspace_root": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#automod@1.0.14",
          "name": "automod",
          "version": "1.0.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/automod-1.0.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/automod-1.0.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.16",
          "name": "cc",
          "version": "1.2.16",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.16/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#dissimilar@1.0.9",
          "name": "dissimilar",
          "version": "1.0.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dissimilar-1.0.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dissimilar-1.0.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.2",
          "name": "equivalent",
          "version": "1.0.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.2",
          "name": "glob",
          "version": "0.3.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.15.2",
          "name": "hashbrown",
          "version": "0.15.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.15.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.15.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.7.1",
          "name": "indexmap",
          "version": "2.7.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.7.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.7.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#indoc@2.0.5",
          "name": "indoc",
          "version": "2.0.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indoc-2.0.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indoc-2.0.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.14",
          "name": "itoa",
          "version": "1.0.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.170",
          "name": "libc",
          "version": "0.2.170",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.170/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.170"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
          "name": "memchr",
          "version": "2.7.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.94",
          "name": "proc-macro2",
          "version": "1.0.94",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.94"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#psm@0.1.25",
          "name": "psm",
          "version": "0.1.25",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/psm-0.1.25/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/psm-0.1.25"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.39",
          "name": "quote",
          "version": "1.0.39",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.39/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.39"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ref-cast@1.0.24",
          "name": "ref-cast",
          "version": "1.0.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-1.0.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-1.0.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ref-cast-impl@1.0.24",
          "name": "ref-cast-impl",
          "version": "1.0.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-impl-1.0.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ref-cast-impl-1.0.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.19",
          "name": "rustversion",
          "version": "1.0.19",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.19/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.19",
          "name": "ryu",
          "version": "1.0.19",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
          "name": "serde",
          "version": "1.0.218",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_bytes@0.11.16",
          "name": "serde_bytes",
          "version": "0.11.16",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_bytes-0.11.16/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_bytes-0.11.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.218",
          "name": "serde_derive",
          "version": "1.0.218",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.218/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.218"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.139",
          "name": "serde_json",
          "version": "1.0.139",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.139/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.139"
        },
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
          "name": "serde_json",
          "version": "1.0.140",
          "manifest_path": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_spanned@0.6.8",
          "name": "serde_spanned",
          "version": "0.6.8",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-0.6.8/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-0.6.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_stacker@0.1.12",
          "name": "serde_stacker",
          "version": "0.1.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_stacker-0.1.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_stacker-0.1.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
          "name": "shlex",
          "version": "1.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#stacker@0.1.19",
          "name": "stacker",
          "version": "0.1.19",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stacker-0.1.19/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stacker-0.1.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.99",
          "name": "syn",
          "version": "2.0.99",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.99/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.99"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-triple@0.1.4",
          "name": "target-triple",
          "version": "0.1.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-0.1.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-0.1.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
          "name": "termcolor",
          "version": "1.4.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml@0.8.20",
          "name": "toml",
          "version": "0.8.20",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.8.20/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-0.8.20"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@0.6.8",
          "name": "toml_datetime",
          "version": "0.6.8",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.6.8/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-0.6.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_edit@0.22.24",
          "name": "toml_edit",
          "version": "0.22.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.22.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_edit-0.22.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.103",
          "name": "trybuild",
          "version": "1.0.103",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.103/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.103"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.17",
          "name": "unicode-ident",
          "version": "1.0.17",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.17/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.17"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.9",
          "name": "winapi-util",
          "version": "0.1.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
          "name": "windows-sys",
          "version": "0.59.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0"
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
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@0.7.3",
          "name": "winnow",
          "version": "0.7.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.7.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-0.7.3"
        }
      ],
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "exit_code": 0,
      "kind": "exec",
      "pid": 51400,
      "ppid": 51263,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "used:cc:b9f1db8b570e5bf6:124c53a02476624e:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
      "pid": 51400,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "used:cc:b9f1db8b570e5bf6:d034368ae7556ed4:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
      "pid": 51400,
      "sha256": "570a94b503a477ebd3545da4d169716edc8bc5411921f7c9756a4224df54d908",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "used:cc:b9f1db8b570e5bf6:d8282c42341a01de:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
      "pid": 51400,
      "sha256": "8702743256d940c3aa508b2ecd830251cb2d8d6941ddf7a48eba1000dd0f6e5f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "used:cc:b9f1db8b570e5bf6:df61e11a738d6b36:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
      "pid": 51400,
      "sha256": "1cbeda0d482ebec946209c09c02e2ee9ea6530cf47c1c0f2db005eab7aeace49",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "used:cc:b9f1db8b570e5bf6:7418c6a869bf20bd:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
      "pid": 51400,
      "sha256": "30a250e4c725df1e0c01195e23cb383a6a11124391099a178b20d9a7ce738094",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "used:cc:b9f1db8b570e5bf6:f1284966aa4a12db:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
      "pid": 51400,
      "sha256": "65f01bdd545f06bb22692b08a5bb2b760bedbdf548b6fb2edab9c82ca7ebb1b3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "used:cc:b9f1db8b570e5bf6:fdf3c311bc58bdb7:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
      "pid": 51400,
      "sha256": "d823d9ff3b33d9402e459193d3b1554744c53c64fccb5984b5dec57d58948294",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "used:cc:b9f1db8b570e5bf6:57e72c7f5e9664f0:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
      "pid": 51400,
      "sha256": "c7e40648779a1725fde38708952d07cb6c92d3195f16771e240e986c9355409c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "used:cc:b9f1db8b570e5bf6:f2902fe3392a3a8d:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
      "pid": 51400,
      "sha256": "250660162e4e638b49f8ee1ed921b3d811bbb533927197dc3389041e0e901abb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "used:cc:b9f1db8b570e5bf6:9e895b8440a09458:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
      "pid": 51400,
      "sha256": "c3786f633cd8e55f38df7c01163d7db848421d8faf0b56756f3e77e4a8b7dd9f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "used:cc:b9f1db8b570e5bf6:8075f17b0b870db0:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
      "pid": 51400,
      "sha256": "7fcb4eb2fb437bc0bc537b6c93b1935273d9bae18d1333b82878b293714891e7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
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
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "context_path": "/tmp/native-trace-50172-1783992780094/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-50172-1783992780094/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 51400,
      "ppid": 51263,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39",
        "/target/debug/build/serde_json-f663e98440021490",
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
          "directory": "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/rustcyJhY39/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.09xf06q.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.09xf06q.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.09xf06q.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.09xf06q.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.09xf06q.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.09xf06q.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.09xf06q.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.09xf06q.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.09xf06q.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.09xf06q.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-51400-1783992784105682433.map",
      "pid": 51400,
      "ppid": 51263,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-51400-1783992784105682433.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
      "exit_code": 0,
      "kind": "exec",
      "pid": 51636,
      "ppid": 51258,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde",
        "version": "1.0.218",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.218",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
      "event_id": "used:cc:bc511c808a7c37c7:4ec85ebe8241ec9d:3bd91b3119723b6e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
      "path": "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
      "pid": 51636,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde",
        "version": "1.0.218",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.218",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
      "event_id": "used:cc:bc511c808a7c37c7:ef0e413b02d274b8:3bd91b3119723b6e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
      "path": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
      "pid": 51636,
      "sha256": "b112d573278ac5b3ac86053b07f90f1f07612cee278867c6c3bba2efe9da4393",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde",
        "version": "1.0.218",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.218",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
      "event_id": "used:cc:bc511c808a7c37c7:9873dfd73ce6c9e9:3bd91b3119723b6e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
      "path": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
      "pid": 51636,
      "sha256": "a485ce845d1b83556f32ad7510c2900c44192736b8c0695d7ee72935eb16077f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde",
        "version": "1.0.218",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
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
      "output": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde",
        "version": "1.0.218",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
      "cargo_pkg_name": "serde",
      "cargo_pkg_version": "1.0.218",
      "context_path": "/tmp/native-trace-50172-1783992780094/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-50172-1783992780094/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 51636,
      "ppid": 51258,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "_owner": {
        "crate": "serde",
        "version": "1.0.218",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ",
        "/target/debug/build/serde-fc0ba381ae66b83b",
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
          "directory": "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ",
          "kind": "object",
          "path": "/target/debug/build/serde-fc0ba381ae66b83b/rustcptt5aQ/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde-fc0ba381ae66b83b",
          "kind": "object",
          "path": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde-fc0ba381ae66b83b",
          "kind": "object",
          "path": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-51636-1783992784399263723.map",
      "pid": 51636,
      "ppid": 51258,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-51636-1783992784399263723.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "serde",
        "version": "1.0.218",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
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
      "parsed_event_count": 765,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 767,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "tainerd/containerd.sock -publish-binary /usr/bin/containerd -id 86bc0bef27803e7498cb120c93515d2273628c95e3b3a4c8553dfb51501e657c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86bc0bef27803e7498cb120c93515d2273628c95e3b3a4c8553dfb51501 delete\n13.323  runc             54186  54173    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/86bc0bef27803e7498cb120c93515d2273628c95e3b3a4c8553dfb51501e657 --log-format json delete --force 86bc0bef27803e7498cb120c93515d2273628c95e3b3a4c8553dfb51501e657c\n13.344  etcdctl          54174  54162    0 /usr/local/bin/etcdctl endpoint health\n13.364  sh               54203  54200    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth697c247\n13.366  ethtool          54204  54203    0 /usr/sbin/ethtool -i veth697c247\n13.366  sed              54205  54203    0 /usr/bin/sed -n s/^driver: //p\n13.373  systemd-sysctl   54208  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth697c247 --prefix=/net/ipv4/neigh/veth697c247 --prefix=/net/ipv6/conf/veth697c247 --prefix=/net/ipv6/neigh/veth697c247\n14.030  runc             54210  46371    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 --log-format json --systemd-cgroup kill --all e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78 9\n14.049  runc             54216  46371    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 --log-format json --systemd-cgroup delete e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78\n14.073  sh               54222  2147557   0 /bin/sh -c which ps\n14.075  which            54222  2147557   0 /usr/bin/which ps\n14.077  sh               54223  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.079  ps               54223  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.116  sh               54224  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n14.118  cpuUsage.sh      54224  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n14.120  sed              54225  54224    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.123  cat              54226  54224    0 /usr/bin/cat /proc/2240539/stat\n14.124  cat              54227  54224    0 /usr/bin/cat /proc/4193716/stat\n14.126  sleep            54228  54224    0 /usr/bin/sleep 1\n14.219  16               54231  1        0 /proc/self/fd/16 --deserialize 145 --log-level info --log-target journal-or-kmsg\n14.222  16               54232  1        0 /proc/self/fd/16 --deserialize 157 --log-level info --log-target journal-or-kmsg\n14.283  containerd-shim  54234  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 delete\n14.286  runc             54241  54234    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e7 --log-format json delete --force e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78\n14.320  systemd-sysctl   54246  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth185aa5a --prefix=/net/ipv4/neigh/veth185aa5a --prefix=/net/ipv6/conf/veth185aa5a --prefix=/net/ipv6/neigh/veth185aa5a\n14.376  drkonqi-coredum  54232  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 890-54230-0\n14.381  systemd-coredum  54231  1        0 /usr/lib/systemd/systemd-coredump\n14.913  9                54257  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n14.919  abrt-server      54258  1118     0 /usr/bin/abrt-server -s\n14.931  drkonqi-coredum  54257  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n14.948  abrt-handle-eve  54259  54258    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:33:18.647156-53364\n14.964  sh               54262  54259    0 /bin/sh -c abrt-action-save-package-data\\n\n14.966  abrt-action-sav  54262  54259    0 /usr/bin/abrt-action-save-package-data\n14.982  9                54265  4003047   0 /proc/self/fd/9 --deserialize 44 --log-level info --log-target auto\n14.986  plasma_waitforn  54265  4003047   0 /usr/bin/plasma_waitforname org.freedesktop.Notifications\n15.030  sh               54267  54259    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n15.032  cut              54269  54267    0 /usr/bin/cut -d: -f1\n15.032  cat              54270  54268    0 /usr/bin/cat uid\n15.033  getent           54268  54267    0 /usr/bin/getent passwd 1000\n15.035  lscpu            54271  54267    0 /usr/bin/lscpu\n15.053  sh               54272  54259    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n15.054  runlevel         54273  54272    0 /usr/bin/runlevel\n15.066  sh               54274  54259    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n15.067  grep             54275  54274    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n15.069  grep             54276  54274    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n15.071  grep             54277  54274    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n15.072  abrt-action-cor  54278  54274    0 /usr/libexec/abrt-action-coredump -x\n15.128  sed              54279  54224    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.131  cat              54280  54224    0 /usr/bin/cat /proc/2240539/stat\n15.134  cat              54282  54224    0 /usr/bin/cat /proc/4193716/stat\n15.140  abrt-action-gen  54284  54274    0 /usr/bin/abrt-action-generate-core-backtrace\n15.197  abrt-action-ana  54285  54274    0 /usr/bin/abrt-action-analyze-vulnerability\n15.199  eu-readelf       54287  54286    0 /usr/bin/eu-readelf -n coredump\n15.200  sed              54289  54286    0 /usr/bin/sed s/[^0-9]//g\n15.200  grep             54288  54286    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n15.203  gdb              54291  54290    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n15.220  iconv            54292  54291    0 /usr/bin/iconv -l\n15.325  abrt-action-ana  54301  54274    0 /usr/bin/abrt-action-analyze-c\n15.339  eu-unstrip       54302  54301    0 /usr/bin/eu-unstrip --core=./coredump -n\n15.359  abrt-action-lis  54303  54274    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n15.424  cat              54305  54304    0 /usr/bin/cat executable\n15.426  cat              54306  54304    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:33:18.647156-53364/uid\n15.428  journalctl       54307  54304    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n15.442  abrt-action-cor  54308  54274    0 /usr/libexec/abrt-action-coredump -r\n15.493  abrt-handle-eve  54309  54258    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.505  sh               54310  54309    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n15.506  dbus-send        54310  54309    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.508  sh               54311  54309    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n15.509  abrt-action-not  54312  54311    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.559  sh               54313  54312    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n15.560  reporter-system  54313  54312    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n16.942  runc             54316  46203    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 --log-format json --systemd-cgroup kill --all c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2 9\n16.951  16               54322  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n16.968  frpc             54322  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n16.970  runc             54327  46203    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 --log-format json --systemd-cgroup delete c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2\n17.002  cross            54333  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.002  rustc            54336  54333    0 \n17.005  rustc            54336  54333    0 /home/xmoe/.cargo/bin/rustc --print target-list /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.019  rustc            54348  54333    0 /home/xmoe/.cargo/bin/rustc -vV\n17.026  rustc            54348  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.038  cargo            54358  54333    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.044  cargo            54358  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.057  rustc            54367  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.069  rustc            54369  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.084  rustc            54373  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.135  rustc            54377  54333    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.141  rustc            54377  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.156  docker           54389  54333    0 /usr/bin/docker --help\n17.162  containerd-shim  54395  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 delete\n17.166  runc             54407  54395    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f --log-format json delete --force c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2\n17.172  docker           54413  54333    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.186  runc             54423  1599     0 /usr/bin/runc --version\n17.190  docker-init      54429  1599     0 /usr/bin/docker-init --version\n17.191  docker           54430  54333    0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.207  runc             54442  1599     0 /usr/bin/runc --version\n17.208  sh               54443  54200    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth7a6f9c6\n17.209  ethtool          54449  54443    0 /usr/sbin/ethtool -i veth7a6f9c6\n17.210  sed              54450  54443    0 /usr/bin/sed -n s/^driver: //p\n17.212  docker-init      54452  1599     0 /usr/bin/docker-init --version\n17.218  systemd-sysctl   54458  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7a6f9c6 --prefix=/net/ipv4/neigh/veth7a6f9c6 --prefix=/net/ipv6/conf/veth7a6f9c6 --prefix=/net/ipv6/neigh/veth7a6f9c6\n17.243  rustup           54459  54333    0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.251  rustup           54468  54333    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.281  rustup           54477  54333    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.311  uname            54486  54333    0 /usr/bin/uname -r\n17.334  docker           54487  54333    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.376  systemd-sysctl   54499  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6023135 --prefix=/net/ipv4/neigh/veth6023135 --prefix=/net/ipv6/conf/veth6023135 --prefix=/net/ipv6/neigh/veth6023135\n17.376  systemd-sysctl   54500  54247    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb507d9f --prefix=/net/ipv4/neigh/vethb507d9f --prefix=/net/ipv6/conf/vethb507d9f --prefix=/net/ipv6/neigh/vethb507d9f\n17.393  containerd-shim  54527  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 start\n17.399  containerd-shim  54537  54527    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 -address /var/run/docker/containerd/containerd.sock\n17.402  cross            54542  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n17.403  rustc            54545  54542    0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.405  runc             54551  54537    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0\n17.413  exe              54566  54551    0 /proc/self/exe init\n17.433  rustc            54545  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.448  rustc            54579  54542    0 /home/xmoe/.cargo/bin/rustc -vV\n17.455  exe              54588  54551    0 /proc/1599/exe -exec-root=/var/run/docker 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 d7da31e8f8e1\n17.479  rustc            54579  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.480  exe              54596  1599     0 /proc/self/exe /var/run/docker/netns/89f6772925ee all false\n17.492  cargo            54606  54542    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.511  runc             54622  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup kill --all 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a 9\n17.520  runc             54628  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup delete 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.525  cargo            54606  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.536  runc             54634  54537    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --log-format json --systemd-cgroup start 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0\n17.540  rustc            54640  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.543  sh               54570  54537    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.544  cargo            54641  54570    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.553  rustc            54643  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.559  cargo-native-tr  54641  54570    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.564  cargo            54645  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.569  rustc            54648  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.578  rustc            54651  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.590  rustc            54654  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.609  rustc            54658  54542    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.631  rustc            54658  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.643  docker           54670  54542    0 /usr/bin/docker --help\n17.647  execsnoop        54676  54641    0 /usr/local/bin/execsnoop -t\n17.648  python3          54676  54641    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.656  docker           54687  54542    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.666  runc             54696  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup kill --all a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 9\n17.667  runc             54697  1599     0 /usr/bin/runc --version\n17.669  docker-init      54708  1599     0 /usr/bin/docker-init --version\n17.670  docker           54709  54542    0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.673  runc             54715  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup delete a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.682  runc             54726  1599     0 /usr/bin/runc --version\n17.685  docker-init      54732  1599     0 /usr/bin/docker-init --version\n17.705  rustup           54733  54542    0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.719  containerd-shim  54743  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b delete\n17.721  runc             54750  54743    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9 --log-format json delete --force 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.729  rustup           54755  54542    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.752  rustup           54764  54542    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.753  systemd-sysctl   54765  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe425dec --prefix=/net/ipv4/neigh/vethe425dec --prefix=/net/ipv6/conf/vethe425dec --prefix=/net/ipv6/neigh/vethe425dec\n17.776  uname            54774  54542    0 /usr/bin/uname -r\n17.794  docker           54775  54542    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.830  systemd-sysctl   54789  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth76e10a3 --prefix=/net/ipv4/neigh/veth76e10a3 --prefix=/net/ipv6/conf/veth76e10a3 --prefix=/net/ipv6/neigh/veth76e10a3\n17.830  systemd-sysctl   54788  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf2069ec --prefix=/net/ipv4/neigh/vethf2069ec --prefix=/net/ipv6/conf/vethf2069ec --prefix=/net/ipv6/neigh/vethf2069ec\n17.845  containerd-shim  54791  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 start\n17.848  containerd-shim  54798  54791    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 -address /var/run/docker/containerd/containerd.sock\n17.852  runc             54808  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.853  containerd-shim  54811  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 delete\n17.855  runc             54820  54811    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f495792 --log-format json delete --force a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.857  exe              54827  54808    0 /proc/self/exe init\n17.892  systemd-sysctl   54832  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7f2e47d --prefix=/net/ipv4/neigh/veth7f2e47d --prefix=/net/ipv6/conf/veth7f2e47d --prefix=/net/ipv6/neigh/veth7f2e47d\n17.907  exe              54838  54808    0 /proc/1599/exe -exec-root=/var/run/docker 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 d7da31e8f8e1\n17.927  exe              54846  1599     0 /proc/self/exe /var/run/docker/netns/3e401da5d4b2 all false\n17.986  runc             54864  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup start 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.992  sh               54831  54798    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.993  cargo            54870  54831    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n18.003  cargo-native-tr  54870  54831    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n18.006  cargo            54871  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.016  rustc            54872  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.028  rustc            54874  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.037  runc             54878  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup kill --all bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 9\n18.054  runc             54885  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup delete bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n18.066  execsnoop        54891  54870    0 /usr/local/bin/execsnoop -t\n18.067  python3          54891  54870    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.080  runc             54894  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup kill --all a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 9\n18.098  runc             54901  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup delete a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.275  containerd-shim  54907  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b delete\n18.277  runc             54914  54907    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf788 --log-format json delete --force bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n18.314  systemd-sysctl   54919  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfb8276c --prefix=/net/ipv4/neigh/vethfb8276c --prefix=/net/ipv6/conf/vethfb8276c --prefix=/net/ipv6/neigh/vethfb8276c\n18.322  containerd-shim  54921  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 delete\n18.324  runc             54928  54921    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f --log-format json delete --force a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n18.368  systemd-sysctl   54933  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth651aca6 --prefix=/net/ipv4/neigh/veth651aca6 --prefix=/net/ipv6/conf/veth651aca6 --prefix=/net/ipv6/neigh/veth651aca6\n18.434  runc             54934  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup kill --all f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 9\n18.451  runc             54940  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup delete f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.631  containerd-shim  54946  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 delete\n18.634  runc             54953  54946    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da9 --log-format json delete --force f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.671  systemd-sysctl   54959  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd600a16 --prefix=/net/ipv4/neigh/vethd600a16 --prefix=/net/ipv6/conf/vethd600a16 --prefix=/net/ipv6/neigh/vethd600a16\n18.739  runc             54961  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup kill --all 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 9\n18.746  runc             54967  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup delete 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.926  containerd-shim  54974  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d delete\n18.928  runc             54981  54974    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d9863 --log-format json delete --force 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.963  systemd-sysctl   54986  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b8f709 --prefix=/net/ipv4/neigh/veth5b8f709 --prefix=/net/ipv6/conf/veth5b8f709 --prefix=/net/ipv6/neigh/veth5b8f709\n19.074  sh               54987  2147557   0 /bin/sh -c which ps\n19.075  which            54987  2147557   0 /usr/bin/which ps\n19.077  sh               54988  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.078  ps               54988  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.103  sh               54989  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n19.104  cpuUsage.sh      54989  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n19.105  sed              54990  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.107  cat              54991  54989    0 /usr/bin/cat /proc/2240539/stat\n19.108  cat              54992  54989    0 /usr/bin/cat /proc/4193716/stat\n19.109  sleep            54993  54989    0 /usr/bin/sleep 1\n19.502  cargo            54994  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n19.515  rustc            54995  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.544  rustc            55001  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.585  cc               55024  55001    0 /tmp/native-trace-54641-1783992801298/shims/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.585  cc               55025  55024    0 /usr/bin/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.588  collect2         55026  55025    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.589  ld.lld           55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781 ...\n19.590  rust-lld         55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.628  build-script-bu  55045  54994    0 /target/debug/build/valuable-0ca3a52e87f47781/build-script-build\n19.632  rustc            55047  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name valuable --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.912  cargo            55059  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n19.925  rustc            55070  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.950  rustc            55113  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.950  rustc            55111  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba1b82e103e0280b ...\n20.049  cc               55188  55113    0 /tmp/native-trace-54870-1783992801742/shims/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n20.050  cc               55189  55188    0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n20.054  collect2         55190  55189    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.055  ld.lld           55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde ...\n20.056  rust-lld         55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.111  sed              55209  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.111  build-script-bu  55210  55059    0 /target/debug/build/proc-macro2-46239aad0aaf2dde/build-script-build\n20.113  cat              55211  54989    0 /usr/bin/cat /proc/2240539/stat\n20.113  rustc            55212  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n20.114  cat              55214  54989    0 /usr/bin/cat /proc/4193716/stat\n20.123  rustc            55217  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-1a2ad12dc9160ce7/out/probe build/probe.rs --target aarch64-unknown-linux-gnu\n20.150  rustc            55222  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.715  cross            55331  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.716  rustc            55334  55331    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.737  rustc            55334  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.749  rustc            55346  55331    0 /home/xmoe/.cargo/bin/rustc -vV\n20.770  rustc            55346  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.780  cargo            55356  55331    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.801  cargo            55356  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.812  rustc            55366  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.814  git              55365  2235138   0 /usr/bin/git config --get commit.template\n20.821  rustc            55368  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.829  git              55369  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n20.832  rustc            55373  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.845  git              55374  2235138   0 /usr/bin/git status -z -uall\n20.857  rustc            55379  55331    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.860  git              55378  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n20.879  rustc            55379  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.890  docker           55391  55331    0 /usr/bin/docker --help\n20.902  docker           55402  55331    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.914  runc             55412  1599     0 /usr/bin/runc --version\n20.917  docker-init      55418  1599     0 /usr/bin/docker-init --version\n20.918  docker           55419  55331    0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.929  runc             55430  1599     0 /usr/bin/runc --version\n20.932  docker-init      55436  1599     0 /usr/bin/docker-init --version\n20.953  rustup           55440  55331    0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.974  rustup           55449  55331    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.995  rustup           55458  55331    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n21.019  uname            55467  55331    0 /usr/bin/uname -r\n21.034  docker           55468  55331    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n21.070  systemd-sysctl   55483  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8170368 --prefix=/net/ipv4/neigh/veth8170368 --prefix=/net/ipv6/conf/veth8170368 --prefix=/net/ipv6/neigh/veth8170368\n21.070  systemd-sysctl   55482  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth81dd9a9 --prefix=/net/ipv4/neigh/veth81dd9a9 --prefix=/net/ipv6/conf/veth81dd9a9 --prefix=/net/ipv6/neigh/veth81dd9a9\n21.084  containerd-shim  55484  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 start\n21.087  containerd-shim  55491  55484    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 -address /var/run/docker/containerd/containerd.sock\n21.091  runc             55501  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n21.095  exe              55509  55501    0 /proc/self/exe init\n21.113  cross            55513  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n21.115  rustc            55520  55513    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.119  rustc            55520  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.129  exe              55532  55501    0 /proc/1599/exe -exec-root=/var/run/docker 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 d7da31e8f8e1\n21.131  rustc            55539  55513    0 /home/xmoe/.cargo/bin/rustc -vV\n21.135  rustc            55539  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.141  cross            55549  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n21.142  rustc            55552  55549    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.145  cargo            55561  55513    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.146  cross            55564  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n21.147  rustc            55567  55564    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.148  exe              55576  1599     0 /proc/self/exe /var/run/docker/netns/8b628a44607d all false\n21.150  cargo            55561  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.152  rustc            55567  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.161  rustc            55596  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.164  rustc            55597  55564    0 /home/xmoe/.cargo/bin/rustc -vV\n21.168  rustc            55552  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.169  rustc            55597  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.170  rustc            55607  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.177  cargo            55614  55564    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.179  rustc            55616  55549    0 /home/xmoe/.cargo/bin/rustc -vV\n21.180  rustc            55625  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.182  cargo            55614  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.193  rustc            55637  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.195  runc             55639  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup start 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n21.200  sh               55511  55491    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n21.201  cargo            55646  55511    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n21.203  rustc            55647  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.206  rustc            55616  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.213  cargo-native-tr  55646  55511    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n21.214  cargo            55652  55549    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.215  rustc            55653  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.217  cargo            55654  55646    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n21.227  rustc            55666  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.236  cargo            55652  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n21.239  rustc            55668  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.247  rustc            55670  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.256  rustc            55674  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.268  rustc            55678  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.304  git              55683  2235138   0 /usr/bin/git worktree list --porcelain\n21.342  cross            55684  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n21.343  rustc            55687  55684    0 /home/xmoe/.cargo/bin/rustc --print target-list\n21.348  rustc            55687  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.359  runc             55701  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup kill --all 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 9\n21.359  rustc            55700  55684    0 /home/xmoe/.cargo/bin/rustc -vV\n21.364  rustc            55700  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.373  cargo            55716  55684    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.376  runc             55725  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup delete 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n21.378  cargo            55716  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.388  rustc            55731  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.397  rustc            55733  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.420  rustc            55737  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n"
    },
    {
      "argv": [
        "/target/debug/build/serde_json-f663e98440021490/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 51536,
      "build_script_target_dir": "serde_json-f663e98440021490",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/serde_json-f663e98440021490/build-script-build",
      "pid": 51536,
      "ppid": 51169,
      "root_cargo_pid": 51169,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/serde-fc0ba381ae66b83b/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 51839,
      "build_script_target_dir": "serde-fc0ba381ae66b83b",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/serde-fc0ba381ae66b83b/build-script-build",
      "pid": 51839,
      "ppid": 51169,
      "root_cargo_pid": 51169,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 51839,
      "build_script_target_dir": "serde-fc0ba381ae66b83b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 51843,
      "ppid": 51839,
      "root_cargo_pid": 51169,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "serde_json",
      "cwd": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "event_id": "bsrun:c42a269c07c36b4f:b53fe9c00a356d6f:135b23063d020806",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/serde_json-f663e98440021490/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
      "out_dir": "/target/debug/build/serde_json-f663e98440021490/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
      "success": true,
      "target": null,
      "version": "1.0.140",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-aarch64-y4svxwdt/src/serde_json-1.0.140",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "serde",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
      "event_id": "bsrun:43533528a723ce4b:574517cea65d8a5b:423607d971467760",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/serde-fc0ba381ae66b83b/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
      "out_dir": "/target/debug/build/serde-fc0ba381ae66b83b/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
      "success": true,
      "target": null,
      "version": "1.0.218",
      "_owner": {
        "crate": "serde",
        "version": "1.0.218",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
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
      "build_script_root_pid": 51839,
      "build_script_target_dir": "serde-fc0ba381ae66b83b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 51843,
      "ppid": 51839,
      "root_cargo_pid": 51169,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 317,
    "crate": "serde_json",
    "version": "1.0.140",
    "crate_id": "2782",
    "version_id": "1466025",
    "downloads": 95602773,
    "cumulative_downloads": 56832721286,
    "cumulative_share_of_global": 0.21248442472415316,
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
