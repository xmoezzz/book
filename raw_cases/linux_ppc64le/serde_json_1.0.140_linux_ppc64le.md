# `serde_json` `1.0.140`

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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y",
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
      "directory": "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51836-1783992784571766651.map",
  "pid": 51836,
  "ppid": 51647,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51836-1783992784571766651.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "workspace_root": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140"
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
      "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
      "name": "serde_json",
      "version": "1.0.140",
      "manifest_path": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140"
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
  "pid": 51925,
  "ppid": 51651,
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

#### Record 3

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
  "event_id": "used:cc:bc511c808a7c37c7:6d0d5e543e2e8d02:3bd91b3119723b6e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
  "path": "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
  "pid": 51925,
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

#### Record 4

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
  "pid": 51925,
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

#### Record 5

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
  "pid": 51925,
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

#### Record 6

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
    "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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

#### Record 7

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
  "context_path": "/tmp/native-trace-50183-1783992780133/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-50183-1783992780133/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 51925,
  "ppid": 51651,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "_owner": {
    "crate": "serde",
    "version": "1.0.218",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.218",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
    "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp",
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
      "directory": "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp",
      "kind": "object",
      "path": "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-51925-1783992784698911953.map",
  "pid": 51925,
  "ppid": 51651,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51925-1783992784698911953.map"
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

#### Record 9

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "exit_code": 0,
  "kind": "exec",
  "pid": 51836,
  "ppid": 51647,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "used:cc:296f86af3f280b30:0a6e12ab45732826:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
  "pid": 51836,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "used:cc:296f86af3f280b30:19a6b8aebdaf2ed3:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
  "pid": 51836,
  "sha256": "5f9f3bc31dc5ed6e77d2d84966aa488476a53c9bf44d96a67c88d4d0ad6f4722",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "used:cc:296f86af3f280b30:10632daabf5e3212:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
  "pid": 51836,
  "sha256": "f4c47b6dd0b93a13184747e65a3229844a42465bb211fd8d30550437600bb2c3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "used:cc:296f86af3f280b30:a2908b7778f07331:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
  "pid": 51836,
  "sha256": "2eca83f3ab8e980f4d8a6198a5dcc753819f08332341fbd13b825c48f7df0b71",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "used:cc:296f86af3f280b30:f89f3f0eacc0fc02:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
  "pid": 51836,
  "sha256": "4fd1090536613a6dbba77d46347998a0784555e14c1fd1399da335c1ab2d9a2e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "used:cc:296f86af3f280b30:7b557460d41ea3d0:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
  "pid": 51836,
  "sha256": "60d655724598bceb8a2f3b2eb8b47e108738a8dd7d4e7add07235f4b89e925f0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "used:cc:296f86af3f280b30:d9df6cce4699d322:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
  "pid": 51836,
  "sha256": "a289e9dd6a470f793165028cf7613382c118e5024af5264b115ff0ff178d78e3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "used:cc:296f86af3f280b30:907a366703cb8de2:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
  "pid": 51836,
  "sha256": "ec5a1c34fed0a7246e4f6883c07833a4dcff1088ebe51cbefe2f2c93d1937a7d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "used:cc:296f86af3f280b30:e1fdd71834466681:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
  "pid": 51836,
  "sha256": "4b47fabe173bbf6641a23b942e370459e9fe8eee9f1000f7bf129d490aa4985d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "used:cc:296f86af3f280b30:6738005f89cc37fd:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
  "pid": 51836,
  "sha256": "c4c9e7c680664acb66137c8147e2e5fff0688738c4a53e0b43dd254444132559",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "used:cc:296f86af3f280b30:a3e6df31ce4e9135:e2805f809323a234",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
  "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
  "pid": 51836,
  "sha256": "7fcb4eb2fb437bc0bc537b6c93b1935273d9bae18d1333b82878b293714891e7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "cargo_pkg_name": "serde_json",
  "cargo_pkg_version": "1.0.140",
  "context_path": "/tmp/native-trace-50183-1783992780133/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-50183-1783992780133/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 51836,
  "ppid": 51647,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
    "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y",
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
      "directory": "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/serde_json-f663e98440021490",
      "kind": "object",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-51836-1783992784571766651.map",
  "pid": 51836,
  "ppid": 51647,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-51836-1783992784571766651.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
  "parse_error_count": 1,
  "parsed_event_count": 723,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 724,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "bin/etcdctl endpoint health\n12.977  sh               54203  54200    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth697c247\n12.979  ethtool          54204  54203    0 /usr/sbin/ethtool -i veth697c247\n12.979  sed              54205  54203    0 /usr/bin/sed -n s/^driver: //p\n12.986  systemd-sysctl   54208  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth697c247 --prefix=/net/ipv4/neigh/veth697c247 --prefix=/net/ipv6/conf/veth697c247 --prefix=/net/ipv6/neigh/veth697c247\n13.643  runc             54210  46371    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 --log-format json --systemd-cgroup kill --all e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78 9\n13.662  runc             54216  46371    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 --log-format json --systemd-cgroup delete e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78\n13.686  sh               54222  2147557   0 /bin/sh -c which ps\n13.688  which            54222  2147557   0 /usr/bin/which ps\n13.690  sh               54223  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.692  ps               54223  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.730  sh               54224  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n13.731  cpuUsage.sh      54224  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n13.733  sed              54225  54224    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n13.737  cat              54226  54224    0 /usr/bin/cat /proc/2240539/stat\n13.738  cat              54227  54224    0 /usr/bin/cat /proc/4193716/stat\n13.739  sleep            54228  54224    0 /usr/bin/sleep 1\n13.832  16               54231  1        0 /proc/self/fd/16 --deserialize 145 --log-level info --log-target journal-or-kmsg\n13.835  16               54232  1        0 /proc/self/fd/16 --deserialize 157 --log-level info --log-target journal-or-kmsg\n13.896  containerd-shim  54234  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 delete\n13.900  runc             54241  54234    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e7 --log-format json delete --force e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78\n13.933  systemd-sysctl   54246  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth185aa5a --prefix=/net/ipv4/neigh/veth185aa5a --prefix=/net/ipv6/conf/veth185aa5a --prefix=/net/ipv6/neigh/veth185aa5a\n13.989  drkonqi-coredum  54232  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 890-54230-0\n13.994  systemd-coredum  54231  1        0 /usr/lib/systemd/systemd-coredump\n14.527  9                54257  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n14.532  abrt-server      54258  1118     0 /usr/bin/abrt-server -s\n14.544  drkonqi-coredum  54257  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n14.561  abrt-handle-eve  54259  54258    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:33:18.647156-53364\n14.578  sh               54262  54259    0 /bin/sh -c abrt-action-save-package-data\\n\n14.579  abrt-action-sav  54262  54259    0 /usr/bin/abrt-action-save-package-data\n14.595  9                54265  4003047   0 /proc/self/fd/9 --deserialize 44 --log-level info --log-target auto\n14.600  plasma_waitforn  54265  4003047   0 /usr/bin/plasma_waitforname org.freedesktop.Notifications\n14.644  sh               54267  54259    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n14.646  cut              54269  54267    0 /usr/bin/cut -d: -f1\n14.646  cat              54270  54268    0 /usr/bin/cat uid\n14.648  getent           54268  54267    0 \n14.649  lscpu            54271  54267    0 /usr/bin/lscpu\n14.666  sh               54272  54259    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n14.668  runlevel         54273  54272    0 /usr/bin/runlevel\n14.679  sh               54274  54259    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n14.681  grep             54275  54274    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n14.682  grep             54276  54274    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n14.684  grep             54277  54274    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n14.687  abrt-action-cor  54278  54274    0 /usr/libexec/abrt-action-coredump -x\n14.742  sed              54279  54224    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.745  cat              54280  54224    0 /usr/bin/cat /proc/2240539/stat\n14.748  cat              54282  54224    0 /usr/bin/cat /proc/4193716/stat\n14.753  abrt-action-gen  54284  54274    0 /usr/bin/abrt-action-generate-core-backtrace\n14.810  abrt-action-ana  54285  54274    0 /usr/bin/abrt-action-analyze-vulnerability\n14.812  eu-readelf       54287  54286    0 /usr/bin/eu-readelf -n coredump\n14.813  sed              54289  54286    0 /usr/bin/sed s/[^0-9]//g\n14.813  grep             54288  54286    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n14.816  gdb              54291  54290    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n14.833  iconv            54292  54291    0 /usr/bin/iconv -l\n14.938  abrt-action-ana  54301  54274    0 /usr/bin/abrt-action-analyze-c\n14.953  eu-unstrip       54302  54301    0 /usr/bin/eu-unstrip --core=./coredump -n\n14.973  abrt-action-lis  54303  54274    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n15.038  cat              54305  54304    0 /usr/bin/cat executable\n15.039  cat              54306  54304    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:33:18.647156-53364/uid\n15.041  journalctl       54307  54304    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n15.055  abrt-action-cor  54308  54274    0 /usr/libexec/abrt-action-coredump -r\n15.106  abrt-handle-eve  54309  54258    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.118  sh               54310  54309    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n15.120  dbus-send        54310  54309    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.121  sh               54311  54309    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n15.123  abrt-action-not  54312  54311    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.172  sh               54313  54312    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n15.173  reporter-system  54313  54312    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n16.555  runc             54316  46203    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 --log-format json --systemd-cgroup kill --all c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2 9\n16.565  16               54322  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n16.581  frpc             54322  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n16.584  runc             54327  46203    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 --log-format json --systemd-cgroup delete c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2\n16.609  cross            54333  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n16.611  rustc            54336  54333    0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.618  rustc            54336  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.632  rustc            54348  54333    0 /home/xmoe/.cargo/bin/rustc -vV\n16.639  rustc            54348  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.651  cargo            54358  54333    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.657  cargo            54358  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.670  rustc            54367  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.683  rustc            54369  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.697  rustc            54373  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.748  rustc            54377  54333    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.755  rustc            54377  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.769  docker           54389  54333    0 /usr/bin/docker --help\n16.776  containerd-shim  54395  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 delete\n16.779  runc             54407  54395    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f --log-format json delete --force c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2\n16.785  docker           54413  54333    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.800  runc             54423  1599     0 /usr/bin/runc --version\n16.803  docker-init      54429  1599     0 /usr/bin/docker-init --version\n16.805  docker           54430  54333    0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.820  runc             54442  1599     0 /usr/bin/runc --version\n16.821  sh               54443  54200    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth7a6f9c6\n16.823  ethtool          54449  54443    0 /usr/sbin/ethtool -i veth7a6f9c6\n16.823  sed              54450  54443    0 /usr/bin/sed -n s/^driver: //p\n16.825  docker-init      54452  1599     0 /usr/bin/docker-init --version\n16.831  systemd-sysctl   54458  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7a6f9c6 --prefix=/net/ipv4/neigh/veth7a6f9c6 --prefix=/net/ipv6/conf/veth7a6f9c6 --prefix=/net/ipv6/neigh/veth7a6f9c6\n16.856  rustup           54459  54333    0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.864  rustup           54468  54333    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.895  rustup           54477  54333    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.925  uname            54486  54333    0 /usr/bin/uname -r\n16.948  docker           54487  54333    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.989  systemd-sysctl   54499  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6023135 --prefix=/net/ipv4/neigh/veth6023135 --prefix=/net/ipv6/conf/veth6023135 --prefix=/net/ipv6/neigh/veth6023135\n16.990  systemd-sysctl   54500  54247    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb507d9f --prefix=/net/ipv4/neigh/vethb507d9f --prefix=/net/ipv6/conf/vethb507d9f --prefix=/net/ipv6/neigh/vethb507d9f\n17.006  containerd-shim  54527  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 start\n17.012  containerd-shim  54537  54527    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 -address /var/run/docker/containerd/containerd.sock\n17.015  cross            54542  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n17.016  rustc            54545  54542    0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.019  runc             54551  54537    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0\n17.026  exe              54566  54551    0 /proc/self/exe init\n17.046  rustc            54545  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.061  rustc            54579  54542    0 /home/xmoe/.cargo/bin/rustc -vV\n17.068  exe              54588  54551    0 /proc/1599/exe -exec-root=/var/run/docker 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 d7da31e8f8e1\n17.092  rustc            54579  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.094  exe              54596  1599     0 /proc/self/exe /var/run/docker/netns/89f6772925ee all false\n17.105  cargo            54606  54542    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.126  runc             54622  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup kill --all 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a 9\n17.133  runc             54628  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup delete 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.138  cargo            54606  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.149  runc             54634  54537    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --log-format json --systemd-cgroup start 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0\n17.154  rustc            54640  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.156  sh               54570  54537    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.157  cargo            54641  54570    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.166  rustc            54643  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.172  cargo-native-tr  54641  54570    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.177  cargo            54645  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.182  rustc            54648  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.191  rustc            54651  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.203  rustc            54654  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.222  rustc            54658  54542    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.244  rustc            54658  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.256  docker           54670  54542    0 /usr/bin/docker --help\n17.260  execsnoop        54676  54641    0 /usr/local/bin/execsnoop -t\n17.261  python3          54676  54641    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.269  docker           54687  54542    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.280  runc             54696  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup kill --all a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 9\n17.280  runc             54697  1599     0 /usr/bin/runc --version\n17.283  docker-init      54708  1599     0 /usr/bin/docker-init --version\n17.284  docker           54709  54542    0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.287  runc             54715  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup delete a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.295  runc             54726  1599     0 /usr/bin/runc --version\n17.298  docker-init      54732  1599     0 /usr/bin/docker-init --version\n17.318  rustup           54733  54542    0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.332  containerd-shim  54743  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b delete\n17.335  runc             54750  54743    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9 --log-format json delete --force 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.342  rustup           54755  54542    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.365  rustup           54764  54542    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.366  systemd-sysctl   54765  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe425dec --prefix=/net/ipv4/neigh/vethe425dec --prefix=/net/ipv6/conf/vethe425dec --prefix=/net/ipv6/neigh/vethe425dec\n17.389  uname            54774  54542    0 /usr/bin/uname -r\n17.407  docker           54775  54542    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.443  systemd-sysctl   54789  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth76e10a3 --prefix=/net/ipv4/neigh/veth76e10a3 --prefix=/net/ipv6/conf/veth76e10a3 --prefix=/net/ipv6/neigh/veth76e10a3\n17.443  systemd-sysctl   54788  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf2069ec --prefix=/net/ipv4/neigh/vethf2069ec --prefix=/net/ipv6/conf/vethf2069ec --prefix=/net/ipv6/neigh/vethf2069ec\n17.458  containerd-shim  54791  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 start\n17.462  containerd-shim  54798  54791    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 -address /var/run/docker/containerd/containerd.sock\n17.465  runc             54808  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.466  containerd-shim  54811  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 delete\n17.469  runc             54820  54811    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f495792 --log-format json delete --force a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.470  exe              54827  54808    0 /proc/self/exe init\n17.506  systemd-sysctl   54832  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7f2e47d --prefix=/net/ipv4/neigh/veth7f2e47d --prefix=/net/ipv6/conf/veth7f2e47d --prefix=/net/ipv6/neigh/veth7f2e47d\n17.520  exe              54838  54808    0 /proc/1599/exe -exec-root=/var/run/docker 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 d7da31e8f8e1\n17.540  exe              54846  1599     0 /proc/self/exe /var/run/docker/netns/3e401da5d4b2 all false\n17.600  runc             54864  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup start 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.605  sh               54831  54798    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.606  cargo            54870  54831    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n17.616  cargo-native-tr  54870  54831    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.619  cargo            54871  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.630  rustc            54872  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.641  rustc            54874  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.651  runc             54878  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup kill --all bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 9\n17.668  runc             54885  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup delete bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n17.679  execsnoop        54891  54870    0 /usr/local/bin/execsnoop -t\n17.680  python3          54891  54870    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.700  runc             54894  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup kill --all a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 9\n17.712  runc             54901  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup delete a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n17.888  containerd-shim  54907  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b delete\n17.891  runc             54914  54907    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf788 --log-format json delete --force bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n17.927  systemd-sysctl   54919  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfb8276c --prefix=/net/ipv4/neigh/vethfb8276c --prefix=/net/ipv6/conf/vethfb8276c --prefix=/net/ipv6/neigh/vethfb8276c\n17.935  containerd-shim  54921  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 delete\n17.938  runc             54928  54921    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f --log-format json delete --force a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n17.981  systemd-sysctl   54933  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth651aca6 --prefix=/net/ipv4/neigh/veth651aca6 --prefix=/net/ipv6/conf/veth651aca6 --prefix=/net/ipv6/neigh/veth651aca6\n18.047  runc             54934  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup kill --all f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 9\n18.064  runc             54940  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup delete f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.244  containerd-shim  54946  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 delete\n18.247  runc             54953  54946    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da9 --log-format json delete --force f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.284  systemd-sysctl   54959  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd600a16 --prefix=/net/ipv4/neigh/vethd600a16 --prefix=/net/ipv6/conf/vethd600a16 --prefix=/net/ipv6/neigh/vethd600a16\n18.353  runc             54961  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup kill --all 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 9\n18.359  runc             54967  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup delete 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.539  containerd-shim  54974  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d delete\n18.541  runc             54981  54974    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d9863 --log-format json delete --force 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.576  systemd-sysctl   54986  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b8f709 --prefix=/net/ipv4/neigh/veth5b8f709 --prefix=/net/ipv6/conf/veth5b8f709 --prefix=/net/ipv6/neigh/veth5b8f709\n18.687  sh               54987  2147557   0 /bin/sh -c which ps\n18.688  which            54987  2147557   0 /usr/bin/which ps\n18.690  sh               54988  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.692  ps               54988  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.716  sh               54989  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.717  cpuUsage.sh      54989  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.718  sed              54990  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.720  cat              54991  54989    0 /usr/bin/cat /proc/2240539/stat\n18.722  cat              54992  54989    0 /usr/bin/cat /proc/4193716/stat\n18.722  sleep            54993  54989    0 /usr/bin/sleep 1\n19.116  cargo            54994  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n19.128  rustc            54995  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.157  rustc            55001  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.198  cc               55024  55001    0 /tmp/native-trace-54641-1783992801298/shims/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.199  cc               55025  55024    0 /usr/bin/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.201  collect2         55026  55025    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.203  ld.lld           55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781 ...\n19.204  rust-lld         55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.242  build-script-bu  55045  54994    0 /target/debug/build/valuable-0ca3a52e87f47781/build-script-build\n19.246  rustc            55047  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name valuable --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.525  cargo            55059  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n19.538  rustc            55070  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.563  rustc            55113  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.564  rustc            55111  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba1b82e103e0280b ...\n19.662  cc               55188  55113    0 /tmp/native-trace-54870-1783992801742/shims/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.663  cc               55189  55188    0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.667  collect2         55190  55189    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.668  ld.lld           55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde ...\n19.670  rust-lld         55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.724  sed              55209  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.724  build-script-bu  55210  55059    0 /target/debug/build/proc-macro2-46239aad0aaf2dde/build-script-build\n19.726  cat              55211  54989    0 /usr/bin/cat /proc/2240539/stat\n19.726  rustc            55212  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.727  cat              55214  54989    0 /usr/bin/cat /proc/4193716/stat\n19.736  rustc            55217  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-1a2ad12dc9160ce7/out/probe build/probe.rs --target aarch64-unknown-linux-gnu\n19.763  rustc            55222  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.328  cross            55331  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.329  rustc            55334  55331    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.350  rustc            55334  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.362  rustc            55346  55331    0 /home/xmoe/.cargo/bin/rustc -vV\n20.384  rustc            55346  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.394  cargo            55356  55331    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.415  cargo            55356  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.425  rustc            55366  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.427  git              55365  2235138   0 /usr/bin/git config --get commit.template\n20.434  rustc            55368  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.442  git              55369  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n20.445  rustc            55373  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.458  git              55374  2235138   0 /usr/bin/git status -z -uall\n20.470  rustc            55379  55331    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.474  git              55378  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n20.492  rustc            55379  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.504  docker           55391  55331    0 /usr/bin/docker --help\n20.516  docker           55402  55331    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.527  runc             55412  1599     0 /usr/bin/runc --version\n20.530  docker-init      55418  1599     0 /usr/bin/docker-init --version\n20.531  docker           55419  55331    0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.542  runc             55430  1599     0 /usr/bin/runc --version\n20.545  docker-init      55436  1599     0 /usr/bin/docker-init --version\n20.566  rustup           55440  55331    0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.587  rustup           55449  55331    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.609  rustup           55458  55331    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.632  uname            55467  55331    0 /usr/bin/uname -r\n20.647  docker           55468  55331    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n20.684  systemd-sysctl   55483  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8170368 --prefix=/net/ipv4/neigh/veth8170368 --prefix=/net/ipv6/conf/veth8170368 --prefix=/net/ipv6/neigh/veth8170368\n20.684  systemd-sysctl   55482  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth81dd9a9 --prefix=/net/ipv4/neigh/veth81dd9a9 --prefix=/net/ipv6/conf/veth81dd9a9 --prefix=/net/ipv6/neigh/veth81dd9a9\n20.697  containerd-shim  55484  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 start\n20.700  containerd-shim  55491  1        0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 -address /var/run/docker/containerd/containerd.sock\n20.704  runc             55501  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.709  exe              55509  55501    0 /proc/self/exe init\n20.727  cross            55513  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.728  rustc            55520  55513    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.733  rustc            55520  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.742  exe              55532  55501    0 /proc/1599/exe -exec-root=/var/run/docker 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 d7da31e8f8e1\n20.744  rustc            55539  55513    0 /home/xmoe/.cargo/bin/rustc -vV\n20.749  rustc            55539  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.754  cross            55549  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.756  rustc            55552  55549    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.758  cargo            55561  55513    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.759  cross            55564  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.760  rustc            55567  55564    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.762  exe              55576  1599     0 /proc/self/exe /var/run/docker/netns/8b628a44607d all false\n20.764  cargo            55561  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.765  rustc            55567  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.774  rustc            55596  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.777  rustc            55597  55564    0 /home/xmoe/.cargo/bin/rustc -vV\n20.781  rustc            55552  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.782  rustc            55597  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.783  rustc            55607  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.791  cargo            55614  55564    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.793  rustc            55616  55549    0 /home/xmoe/.cargo/bin/rustc -vV\n20.794  rustc            55625  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.796  cargo            55614  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.806  rustc            55637  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.808  runc             55639  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup start 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.813  sh               55511  55491    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n20.814  cargo            55646  55511    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.816  rustc            55647  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.819  rustc            55616  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.827  cargo-native-tr  55646  55511    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.827  cargo            55652  55549    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.828  rustc            55653  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.830  cargo            55654  55646    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n20.840  rustc            55666  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.849  cargo            55652  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.852  rustc            55668  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.860  rustc            55670  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.869  rustc            55674  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.881  rustc            55678  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.917  git              55683  2235138   0 /usr/bin/git worktree list --porcelain\n20.955  cross            55684  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n20.956  rustc            55687  55684    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.961  rustc            55687  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.972  runc             55701  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup kill --all 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 9\n20.972  rustc            55700  55684    0 /home/xmoe/.cargo/bin/rustc -vV\n20.978  rustc            55700  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.986  cargo            55716  55684    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n20.989  runc             55725  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup delete 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n20.991  cargo            55716  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.001  rustc            55731  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.010  rustc            55733  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.033  rustc            55737  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.118  runc             55741  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup kill --all f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e 9\n21.126  runc             55748  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup delete f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n"
}
```

#### Record 26

```json
{
  "argv": [
    "/target/debug/build/serde_json-f663e98440021490/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 52064,
  "build_script_target_dir": "serde_json-f663e98440021490",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/serde_json-f663e98440021490/build-script-build",
  "pid": 52064,
  "ppid": 51532,
  "root_cargo_pid": 51532,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "_build_script_out_dir": "/target/debug/build/serde_json-f663e98440021490/out"
}
```

#### Record 27

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

#### Record 28

```json
{
  "crate": "serde_json",
  "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "event_id": "bsrun:769c25bda3f61aad:b53fe9c00a356d6f:135b23063d020806",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/serde_json-f663e98440021490/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
  "out_dir": "/target/debug/build/serde_json-f663e98440021490/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
  "success": true,
  "target": null,
  "version": "1.0.140",
  "_owner": {
    "crate": "serde_json",
    "version": "1.0.140",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
    "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:33:25.657411+00:00",
  "crate": "serde_json",
  "version": "1.0.140",
  "architecture": "ppc64le",
  "duration_seconds": 29.093652789946645,
  "trace_record_count": 28,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "manifest_path": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140/Cargo.toml"
      }
    ],
    "attributed_event_count": 25,
    "unattributed_event_count": 3,
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "workspace_root": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140"
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
          "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
          "name": "serde_json",
          "version": "1.0.140",
          "manifest_path": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140"
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
      "pid": 51925,
      "ppid": 51651,
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
      "event_id": "used:cc:bc511c808a7c37c7:6d0d5e543e2e8d02:3bd91b3119723b6e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b",
      "path": "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
      "pid": 51925,
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
      "pid": 51925,
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
      "pid": 51925,
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.build_script_build.c21e7ae34bb47cfc-cgu.0.rcgu.o",
        "/target/debug/build/serde-fc0ba381ae66b83b/build_script_build-fc0ba381ae66b83b.0mdy8g4iippii72abl5amqmxs.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
      "context_path": "/tmp/native-trace-50183-1783992780133/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.218",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-50183-1783992780133/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 51925,
      "ppid": 51651,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/raw-dylibs",
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
        "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp",
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
          "directory": "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp",
          "kind": "object",
          "path": "/target/debug/build/serde-fc0ba381ae66b83b/rustcAyIHNp/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-51925-1783992784698911953.map",
      "pid": 51925,
      "ppid": 51651,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-51925-1783992784698911953.map"
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
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "exit_code": 0,
      "kind": "exec",
      "pid": 51836,
      "ppid": 51647,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "used:cc:296f86af3f280b30:0a6e12ab45732826:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
      "pid": 51836,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "used:cc:296f86af3f280b30:19a6b8aebdaf2ed3:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
      "pid": 51836,
      "sha256": "5f9f3bc31dc5ed6e77d2d84966aa488476a53c9bf44d96a67c88d4d0ad6f4722",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "used:cc:296f86af3f280b30:10632daabf5e3212:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
      "pid": 51836,
      "sha256": "f4c47b6dd0b93a13184747e65a3229844a42465bb211fd8d30550437600bb2c3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "used:cc:296f86af3f280b30:a2908b7778f07331:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
      "pid": 51836,
      "sha256": "2eca83f3ab8e980f4d8a6198a5dcc753819f08332341fbd13b825c48f7df0b71",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "used:cc:296f86af3f280b30:f89f3f0eacc0fc02:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
      "pid": 51836,
      "sha256": "4fd1090536613a6dbba77d46347998a0784555e14c1fd1399da335c1ab2d9a2e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "used:cc:296f86af3f280b30:7b557460d41ea3d0:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
      "pid": 51836,
      "sha256": "60d655724598bceb8a2f3b2eb8b47e108738a8dd7d4e7add07235f4b89e925f0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "used:cc:296f86af3f280b30:d9df6cce4699d322:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
      "pid": 51836,
      "sha256": "a289e9dd6a470f793165028cf7613382c118e5024af5264b115ff0ff178d78e3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "used:cc:296f86af3f280b30:907a366703cb8de2:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
      "pid": 51836,
      "sha256": "ec5a1c34fed0a7246e4f6883c07833a4dcff1088ebe51cbefe2f2c93d1937a7d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "used:cc:296f86af3f280b30:e1fdd71834466681:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
      "pid": 51836,
      "sha256": "4b47fabe173bbf6641a23b942e370459e9fe8eee9f1000f7bf129d490aa4985d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "used:cc:296f86af3f280b30:6738005f89cc37fd:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
      "pid": 51836,
      "sha256": "c4c9e7c680664acb66137c8147e2e5fff0688738c4a53e0b43dd254444132559",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "used:cc:296f86af3f280b30:a3e6df31ce4e9135:e2805f809323a234",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490",
      "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
      "pid": 51836,
      "sha256": "7fcb4eb2fb437bc0bc537b6c93b1935273d9bae18d1333b82878b293714891e7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "cargo_pkg_name": "serde_json",
      "cargo_pkg_version": "1.0.140",
      "context_path": "/tmp/native-trace-50183-1783992780133/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-50183-1783992780133/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 51836,
      "ppid": 51647,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
        "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y",
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
          "directory": "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/rustcwrIh6Y/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.0adag7j2okrlzt650fsdyh43x.0mzrtcw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.2sx8fb09wggsw7ghhhjaaihk5.0mzrtcw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.5n9mhnlt9d05v68uysd03g76u.0mzrtcw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.7ziqefj841bcdjkc3phj0nyqe.0mzrtcw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.aig42fsesi0fti05xzveg73z1.0mzrtcw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.bl822i1qil49c49mgdgjoov4b.0mzrtcw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.dcel29yyydj1tfwu8fhh6qhz4.0mzrtcw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.e0a64eh3t5lz6ty8vuemuju31.0mzrtcw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.en9y7r32iehex2tt94ma01wky.0mzrtcw.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/serde_json-f663e98440021490",
          "kind": "object",
          "path": "/target/debug/build/serde_json-f663e98440021490/build_script_build-f663e98440021490.cb1x0z555p2eqmhayxdtxzmfv.0mzrtcw.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-51836-1783992784571766651.map",
      "pid": 51836,
      "ppid": 51647,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-51836-1783992784571766651.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
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
      "parsed_event_count": 723,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 724,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "bin/etcdctl endpoint health\n12.977  sh               54203  54200    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth697c247\n12.979  ethtool          54204  54203    0 /usr/sbin/ethtool -i veth697c247\n12.979  sed              54205  54203    0 /usr/bin/sed -n s/^driver: //p\n12.986  systemd-sysctl   54208  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth697c247 --prefix=/net/ipv4/neigh/veth697c247 --prefix=/net/ipv6/conf/veth697c247 --prefix=/net/ipv6/neigh/veth697c247\n13.643  runc             54210  46371    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 --log-format json --systemd-cgroup kill --all e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78 9\n13.662  runc             54216  46371    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 --log-format json --systemd-cgroup delete e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78\n13.686  sh               54222  2147557   0 /bin/sh -c which ps\n13.688  which            54222  2147557   0 /usr/bin/which ps\n13.690  sh               54223  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.692  ps               54223  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.730  sh               54224  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n13.731  cpuUsage.sh      54224  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n13.733  sed              54225  54224    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n13.737  cat              54226  54224    0 /usr/bin/cat /proc/2240539/stat\n13.738  cat              54227  54224    0 /usr/bin/cat /proc/4193716/stat\n13.739  sleep            54228  54224    0 /usr/bin/sleep 1\n13.832  16               54231  1        0 /proc/self/fd/16 --deserialize 145 --log-level info --log-target journal-or-kmsg\n13.835  16               54232  1        0 /proc/self/fd/16 --deserialize 157 --log-level info --log-target journal-or-kmsg\n13.896  containerd-shim  54234  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7 delete\n13.900  runc             54241  54234    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e7 --log-format json delete --force e5f820ccb05a39a26680da1081e1be66fa71149415efeeb2e5ae1b553d7a5e78\n13.933  systemd-sysctl   54246  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth185aa5a --prefix=/net/ipv4/neigh/veth185aa5a --prefix=/net/ipv6/conf/veth185aa5a --prefix=/net/ipv6/neigh/veth185aa5a\n13.989  drkonqi-coredum  54232  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 890-54230-0\n13.994  systemd-coredum  54231  1        0 /usr/lib/systemd/systemd-coredump\n14.527  9                54257  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n14.532  abrt-server      54258  1118     0 /usr/bin/abrt-server -s\n14.544  drkonqi-coredum  54257  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n14.561  abrt-handle-eve  54259  54258    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:33:18.647156-53364\n14.578  sh               54262  54259    0 /bin/sh -c abrt-action-save-package-data\\n\n14.579  abrt-action-sav  54262  54259    0 /usr/bin/abrt-action-save-package-data\n14.595  9                54265  4003047   0 /proc/self/fd/9 --deserialize 44 --log-level info --log-target auto\n14.600  plasma_waitforn  54265  4003047   0 /usr/bin/plasma_waitforname org.freedesktop.Notifications\n14.644  sh               54267  54259    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n14.646  cut              54269  54267    0 /usr/bin/cut -d: -f1\n14.646  cat              54270  54268    0 /usr/bin/cat uid\n14.648  getent           54268  54267    0 \n14.649  lscpu            54271  54267    0 /usr/bin/lscpu\n14.666  sh               54272  54259    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n14.668  runlevel         54273  54272    0 /usr/bin/runlevel\n14.679  sh               54274  54259    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n14.681  grep             54275  54274    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n14.682  grep             54276  54274    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n14.684  grep             54277  54274    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n14.687  abrt-action-cor  54278  54274    0 /usr/libexec/abrt-action-coredump -x\n14.742  sed              54279  54224    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.745  cat              54280  54224    0 /usr/bin/cat /proc/2240539/stat\n14.748  cat              54282  54224    0 /usr/bin/cat /proc/4193716/stat\n14.753  abrt-action-gen  54284  54274    0 /usr/bin/abrt-action-generate-core-backtrace\n14.810  abrt-action-ana  54285  54274    0 /usr/bin/abrt-action-analyze-vulnerability\n14.812  eu-readelf       54287  54286    0 /usr/bin/eu-readelf -n coredump\n14.813  sed              54289  54286    0 /usr/bin/sed s/[^0-9]//g\n14.813  grep             54288  54286    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n14.816  gdb              54291  54290    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n14.833  iconv            54292  54291    0 /usr/bin/iconv -l\n14.938  abrt-action-ana  54301  54274    0 /usr/bin/abrt-action-analyze-c\n14.953  eu-unstrip       54302  54301    0 /usr/bin/eu-unstrip --core=./coredump -n\n14.973  abrt-action-lis  54303  54274    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n15.038  cat              54305  54304    0 /usr/bin/cat executable\n15.039  cat              54306  54304    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:33:18.647156-53364/uid\n15.041  journalctl       54307  54304    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n15.055  abrt-action-cor  54308  54274    0 /usr/libexec/abrt-action-coredump -r\n15.106  abrt-handle-eve  54309  54258    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.118  sh               54310  54309    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n15.120  dbus-send        54310  54309    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.121  sh               54311  54309    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n15.123  abrt-action-not  54312  54311    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n15.172  sh               54313  54312    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n15.173  reporter-system  54313  54312    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n16.555  runc             54316  46203    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 --log-format json --systemd-cgroup kill --all c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2 9\n16.565  16               54322  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n16.581  frpc             54322  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n16.584  runc             54327  46203    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 --log-format json --systemd-cgroup delete c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2\n16.609  cross            54333  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n16.611  rustc            54336  54333    0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.618  rustc            54336  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.632  rustc            54348  54333    0 /home/xmoe/.cargo/bin/rustc -vV\n16.639  rustc            54348  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.651  cargo            54358  54333    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.657  cargo            54358  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.670  rustc            54367  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.683  rustc            54369  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.697  rustc            54373  54358    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.748  rustc            54377  54333    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.755  rustc            54377  54333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.769  docker           54389  54333    0 /usr/bin/docker --help\n16.776  containerd-shim  54395  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934 delete\n16.779  runc             54407  54395    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f --log-format json delete --force c44a67b1e44cdc0d9ce6ba8edf80bbfb436ad0b3f8ceaf8a4b48e706934398f2\n16.785  docker           54413  54333    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.800  runc             54423  1599     0 /usr/bin/runc --version\n16.803  docker-init      54429  1599     0 /usr/bin/docker-init --version\n16.805  docker           54430  54333    0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.820  runc             54442  1599     0 /usr/bin/runc --version\n16.821  sh               54443  54200    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth7a6f9c6\n16.823  ethtool          54449  54443    0 /usr/sbin/ethtool -i veth7a6f9c6\n16.823  sed              54450  54443    0 /usr/bin/sed -n s/^driver: //p\n16.825  docker-init      54452  1599     0 /usr/bin/docker-init --version\n16.831  systemd-sysctl   54458  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7a6f9c6 --prefix=/net/ipv4/neigh/veth7a6f9c6 --prefix=/net/ipv6/conf/veth7a6f9c6 --prefix=/net/ipv6/neigh/veth7a6f9c6\n16.856  rustup           54459  54333    0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.864  rustup           54468  54333    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.895  rustup           54477  54333    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.925  uname            54486  54333    0 /usr/bin/uname -r\n16.948  docker           54487  54333    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.989  systemd-sysctl   54499  54200    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6023135 --prefix=/net/ipv4/neigh/veth6023135 --prefix=/net/ipv6/conf/veth6023135 --prefix=/net/ipv6/neigh/veth6023135\n16.990  systemd-sysctl   54500  54247    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb507d9f --prefix=/net/ipv4/neigh/vethb507d9f --prefix=/net/ipv6/conf/vethb507d9f --prefix=/net/ipv6/neigh/vethb507d9f\n17.006  containerd-shim  54527  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 start\n17.012  containerd-shim  54537  54527    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 -address /var/run/docker/containerd/containerd.sock\n17.015  cross            54542  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n17.016  rustc            54545  54542    0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.019  runc             54551  54537    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0\n17.026  exe              54566  54551    0 /proc/self/exe init\n17.046  rustc            54545  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.061  rustc            54579  54542    0 /home/xmoe/.cargo/bin/rustc -vV\n17.068  exe              54588  54551    0 /proc/1599/exe -exec-root=/var/run/docker 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0 d7da31e8f8e1\n17.092  rustc            54579  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.094  exe              54596  1599     0 /proc/self/exe /var/run/docker/netns/89f6772925ee all false\n17.105  cargo            54606  54542    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.126  runc             54622  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup kill --all 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a 9\n17.133  runc             54628  49060    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b --log-format json --systemd-cgroup delete 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.138  cargo            54606  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.149  runc             54634  54537    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc031 --log-format json --systemd-cgroup start 6e25e4a44bcad616836228a265f0fdf7f60fa8198ae807d77d0106fc0314d8f0\n17.154  rustc            54640  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.156  sh               54570  54537    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.157  cargo            54641  54570    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.166  rustc            54643  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.172  cargo-native-tr  54641  54570    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.177  cargo            54645  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.182  rustc            54648  54606    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.191  rustc            54651  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.203  rustc            54654  54645    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.222  rustc            54658  54542    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.244  rustc            54658  54542    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.256  docker           54670  54542    0 /usr/bin/docker --help\n17.260  execsnoop        54676  54641    0 /usr/local/bin/execsnoop -t\n17.261  python3          54676  54641    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.269  docker           54687  54542    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.280  runc             54696  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup kill --all a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 9\n17.280  runc             54697  1599     0 /usr/bin/runc --version\n17.283  docker-init      54708  1599     0 /usr/bin/docker-init --version\n17.284  docker           54709  54542    0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.287  runc             54715  46492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 --log-format json --systemd-cgroup delete a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.295  runc             54726  1599     0 /usr/bin/runc --version\n17.298  docker-init      54732  1599     0 /usr/bin/docker-init --version\n17.318  rustup           54733  54542    0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.332  containerd-shim  54743  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892b delete\n17.335  runc             54750  54743    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9 --log-format json delete --force 9ed58d3047be895e15a83569f21b31f4cf9beb1c6a5e0d70062476e892bd5a9a\n17.342  rustup           54755  54542    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.365  rustup           54764  54542    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.366  systemd-sysctl   54765  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe425dec --prefix=/net/ipv4/neigh/vethe425dec --prefix=/net/ipv6/conf/vethe425dec --prefix=/net/ipv6/neigh/vethe425dec\n17.389  uname            54774  54542    0 /usr/bin/uname -r\n17.407  docker           54775  54542    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.443  systemd-sysctl   54789  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth76e10a3 --prefix=/net/ipv4/neigh/veth76e10a3 --prefix=/net/ipv6/conf/veth76e10a3 --prefix=/net/ipv6/neigh/veth76e10a3\n17.443  systemd-sysctl   54788  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf2069ec --prefix=/net/ipv4/neigh/vethf2069ec --prefix=/net/ipv6/conf/vethf2069ec --prefix=/net/ipv6/neigh/vethf2069ec\n17.458  containerd-shim  54791  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 start\n17.462  containerd-shim  54798  54791    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 -address /var/run/docker/containerd/containerd.sock\n17.465  runc             54808  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.466  containerd-shim  54811  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f49 delete\n17.469  runc             54820  54811    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f495792 --log-format json delete --force a05961bc2ce1d36699e88cc820faefa6fcbe01877421c4f9d8c6fd67f4957922\n17.470  exe              54827  54808    0 /proc/self/exe init\n17.506  systemd-sysctl   54832  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7f2e47d --prefix=/net/ipv4/neigh/veth7f2e47d --prefix=/net/ipv6/conf/veth7f2e47d --prefix=/net/ipv6/neigh/veth7f2e47d\n17.520  exe              54838  54808    0 /proc/1599/exe -exec-root=/var/run/docker 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10 d7da31e8f8e1\n17.540  exe              54846  1599     0 /proc/self/exe /var/run/docker/netns/3e401da5d4b2 all false\n17.600  runc             54864  54798    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3 --log-format json --systemd-cgroup start 479ff8cb0ab092501b81622bf41663319c43afbdd3a8d173dced3ef14d3b4d10\n17.605  sh               54831  54798    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.606  cargo            54870  54831    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n17.616  cargo-native-tr  54870  54831    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.619  cargo            54871  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.630  rustc            54872  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.641  rustc            54874  54871    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.651  runc             54878  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup kill --all bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 9\n17.668  runc             54885  49386    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b --log-format json --systemd-cgroup delete bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n17.679  execsnoop        54891  54870    0 /usr/local/bin/execsnoop -t\n17.680  python3          54891  54870    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.700  runc             54894  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup kill --all a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 9\n17.712  runc             54901  49353    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 --log-format json --systemd-cgroup delete a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n17.888  containerd-shim  54907  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6b delete\n17.891  runc             54914  54907    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf788 --log-format json delete --force bcf9c402e1804e609381d8fd846a2b1deae11b4198be8515f8d4a9cba6bf7888\n17.927  systemd-sysctl   54919  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfb8276c --prefix=/net/ipv4/neigh/vethfb8276c --prefix=/net/ipv6/conf/vethfb8276c --prefix=/net/ipv6/neigh/vethfb8276c\n17.935  containerd-shim  54921  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5 delete\n17.938  runc             54928  54921    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f --log-format json delete --force a76b4558678c69bd21776c7f6ceb932313e297b2413a562b3617e9bfcf5ec1f7\n17.981  systemd-sysctl   54933  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth651aca6 --prefix=/net/ipv4/neigh/veth651aca6 --prefix=/net/ipv6/conf/veth651aca6 --prefix=/net/ipv6/neigh/veth651aca6\n18.047  runc             54934  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup kill --all f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 9\n18.064  runc             54940  49256    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 --log-format json --systemd-cgroup delete f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.244  containerd-shim  54946  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a40 delete\n18.247  runc             54953  54946    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da9 --log-format json delete --force f68c25eec258e67f7e1c093136aa11070383307f138a5a585a5b46e7a402da96\n18.284  systemd-sysctl   54959  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd600a16 --prefix=/net/ipv4/neigh/vethd600a16 --prefix=/net/ipv6/conf/vethd600a16 --prefix=/net/ipv6/neigh/vethd600a16\n18.353  runc             54961  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup kill --all 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 9\n18.359  runc             54967  49929    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d --log-format json --systemd-cgroup delete 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.539  containerd-shim  54974  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d delete\n18.541  runc             54981  54974    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d9863 --log-format json delete --force 01ae8fde96d3f5aabd71f830a07438ba2ff399c49ea743d7f16d6351f7d98637\n18.576  systemd-sysctl   54986  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b8f709 --prefix=/net/ipv4/neigh/veth5b8f709 --prefix=/net/ipv6/conf/veth5b8f709 --prefix=/net/ipv6/neigh/veth5b8f709\n18.687  sh               54987  2147557   0 /bin/sh -c which ps\n18.688  which            54987  2147557   0 /usr/bin/which ps\n18.690  sh               54988  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.692  ps               54988  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.716  sh               54989  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.717  cpuUsage.sh      54989  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.718  sed              54990  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.720  cat              54991  54989    0 /usr/bin/cat /proc/2240539/stat\n18.722  cat              54992  54989    0 /usr/bin/cat /proc/4193716/stat\n18.722  sleep            54993  54989    0 /usr/bin/sleep 1\n19.116  cargo            54994  54641    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n19.128  rustc            54995  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.157  rustc            55001  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.198  cc               55024  55001    0 /tmp/native-trace-54641-1783992801298/shims/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.199  cc               55025  55024    0 /usr/bin/cc -m64 /target/debug/build/valuable-0ca3a52e87f47781/rustcum31Fu/symbols.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2bcuvqydoknozqmp1me20ruil.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2hvolwvrh1z7h0esed9fdlkq6.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.2ydqatcbwpyv0nfser2rvjw0s.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.320kk89i2c31bqlrt1pe5ftwu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.3dorb0xb6tyxiuzsrh06fg7wn.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.44p8ua3isbvp2so96dfqsrcv0.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.4mgnn3dy9r06fb4dhef909zhp.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54olwytbg728sxv8s6jzea9ac.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.54xlj1thl6ekctt4ryak72mpk.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5gyye0zaqcjlw0qa72458hp4p.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.5m686vmv93io6lluiiyhiylju.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.7d19io80brmbzee20rw5urjmi.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.b7inlg8jykc014dunu01jjkqu.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.c3a0y0h3kjig5bmjwukot6pmm.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.deexadt1dri1ihovsh8z1lp29.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.dlbacscotl41na11230m8gkv8.15hdgiv.rcgu.o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781.e0jqet5ubfmmb5vnbm2c21wdk.15hdgiv.rcgu.o ...\n19.201  collect2         55026  55025    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.203  ld.lld           55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/valuable-0ca3a52e87f47781/build_script_build-0ca3a52e87f47781 ...\n19.204  rust-lld         55027  55026    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjLR4XT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.242  build-script-bu  55045  54994    0 /target/debug/build/valuable-0ca3a52e87f47781/build-script-build\n19.246  rustc            55047  54994    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name valuable --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n19.525  cargo            55059  54870    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n19.538  rustc            55070  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n19.563  rustc            55113  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.564  rustc            55111  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.18/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba1b82e103e0280b ...\n19.662  cc               55188  55113    0 /tmp/native-trace-54870-1783992801742/shims/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.663  cc               55189  55188    0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-46239aad0aaf2dde/rustcz8FJmv/symbols.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0bv3et31ep2k9sd4r4xv6yltt.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0edhhq7oafgl2yf0nrxumcg9r.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0g0902jm3uya6wioho7beok0j.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0owef7ksnbk6ukcc2242nefkr.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.0rdzizyhqamtksvgo7enpq5az.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1r69zij4wcxunk2gd17a0kpg6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1sghvgwc08k4idxie37yo3pw0.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.1wbfjtyvleo9dhvql6dw9ezks.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2om80ctxk1ydfs1240ujhhg0b.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.2ylb2sbb9n609gy1nl3eivm1m.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.34jg2bcz8z6kfpvajxful9pig.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3dgkawms7tf7icnefiv8uh2ur.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3h5kxyomdhio13fti327b3ul4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3pfht32bkan9uc6xs96laffv6.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3vy5vc4kvl4zobt41ffusuic4.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.3wfb4bv7o9ei3djc1ma3hgool.0uq14k2.rcgu.o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde.4sen9su2ywavj025286hzh4rs.0uq14k2.rcgu.o ...\n19.667  collect2         55190  55189    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.668  ld.lld           55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-46239aad0aaf2dde/build_script_build-46239aad0aaf2dde ...\n19.670  rust-lld         55191  55190    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVztFjm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.724  sed              55209  54989    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.724  build-script-bu  55210  55059    0 /target/debug/build/proc-macro2-46239aad0aaf2dde/build-script-build\n19.726  cat              55211  54989    0 /usr/bin/cat /proc/2240539/stat\n19.726  rustc            55212  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.727  cat              55214  54989    0 /usr/bin/cat /proc/4193716/stat\n19.736  rustc            55217  55210    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-1a2ad12dc9160ce7/out/probe build/probe.rs --target aarch64-unknown-linux-gnu\n19.763  rustc            55222  55059    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.328  cross            55331  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.329  rustc            55334  55331    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.350  rustc            55334  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.362  rustc            55346  55331    0 /home/xmoe/.cargo/bin/rustc -vV\n20.384  rustc            55346  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.394  cargo            55356  55331    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.415  cargo            55356  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.425  rustc            55366  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.427  git              55365  2235138   0 /usr/bin/git config --get commit.template\n20.434  rustc            55368  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.442  git              55369  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n20.445  rustc            55373  55356    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.458  git              55374  2235138   0 /usr/bin/git status -z -uall\n20.470  rustc            55379  55331    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.474  git              55378  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n20.492  rustc            55379  55331    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.504  docker           55391  55331    0 /usr/bin/docker --help\n20.516  docker           55402  55331    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.527  runc             55412  1599     0 /usr/bin/runc --version\n20.530  docker-init      55418  1599     0 /usr/bin/docker-init --version\n20.531  docker           55419  55331    0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.542  runc             55430  1599     0 /usr/bin/runc --version\n20.545  docker-init      55436  1599     0 /usr/bin/docker-init --version\n20.566  rustup           55440  55331    0 /home/xmoe/.cargo/bin/rustup toolchain list\n20.587  rustup           55449  55331    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n20.609  rustup           55458  55331    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n20.632  uname            55467  55331    0 /usr/bin/uname -r\n20.647  docker           55468  55331    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n20.684  systemd-sysctl   55483  54519    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8170368 --prefix=/net/ipv4/neigh/veth8170368 --prefix=/net/ipv6/conf/veth8170368 --prefix=/net/ipv6/neigh/veth8170368\n20.684  systemd-sysctl   55482  54524    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth81dd9a9 --prefix=/net/ipv4/neigh/veth81dd9a9 --prefix=/net/ipv6/conf/veth81dd9a9 --prefix=/net/ipv6/neigh/veth81dd9a9\n20.697  containerd-shim  55484  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 start\n20.700  containerd-shim  55491  1        0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 -address /var/run/docker/containerd/containerd.sock\n20.704  runc             55501  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.709  exe              55509  55501    0 /proc/self/exe init\n20.727  cross            55513  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.728  rustc            55520  55513    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.733  rustc            55520  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.742  exe              55532  55501    0 /proc/1599/exe -exec-root=/var/run/docker 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956 d7da31e8f8e1\n20.744  rustc            55539  55513    0 /home/xmoe/.cargo/bin/rustc -vV\n20.749  rustc            55539  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.754  cross            55549  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n20.756  rustc            55552  55549    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.758  cargo            55561  55513    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.759  cross            55564  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.760  rustc            55567  55564    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.762  exe              55576  1599     0 /proc/self/exe /var/run/docker/netns/8b628a44607d all false\n20.764  cargo            55561  55513    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.765  rustc            55567  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.774  rustc            55596  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.777  rustc            55597  55564    0 /home/xmoe/.cargo/bin/rustc -vV\n20.781  rustc            55552  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.782  rustc            55597  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.783  rustc            55607  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.791  cargo            55614  55564    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.793  rustc            55616  55549    0 /home/xmoe/.cargo/bin/rustc -vV\n20.794  rustc            55625  55561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.796  cargo            55614  55564    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.806  rustc            55637  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.808  runc             55639  55491    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435e --log-format json --systemd-cgroup start 8e0e522205805e705c5c15babb36d05d1acf191276f124824e3cf86435ec4956\n20.813  sh               55511  55491    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n20.814  cargo            55646  55511    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.816  rustc            55647  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.819  rustc            55616  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.827  cargo-native-tr  55646  55511    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n20.827  cargo            55652  55549    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.828  rustc            55653  55614    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.830  cargo            55654  55646    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n20.840  rustc            55666  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.849  cargo            55652  55549    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n20.852  rustc            55668  55654    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.860  rustc            55670  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.869  rustc            55674  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.881  rustc            55678  55652    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.917  git              55683  2235138   0 /usr/bin/git worktree list --porcelain\n20.955  cross            55684  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n20.956  rustc            55687  55684    0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.961  rustc            55687  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.972  runc             55701  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup kill --all 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9 9\n20.972  rustc            55700  55684    0 /home/xmoe/.cargo/bin/rustc -vV\n20.978  rustc            55700  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.986  cargo            55716  55684    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n20.989  runc             55725  47737    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a --log-format json --systemd-cgroup delete 2db8d70cc8e29cb47161ea1ffc6ef0a3e23b52aba0c8ce68779c88c414a7b3a9\n20.991  cargo            55716  55684    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n21.001  rustc            55731  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.010  rustc            55733  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.033  rustc            55737  55716    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.118  runc             55741  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup kill --all f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e 9\n21.126  runc             55748  49799    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e --log-format json --systemd-cgroup delete f579dca65fa2f0af189a2ef23a8ec6d092ce495077d7f7a25bf445c913e2fc1e\n"
    },
    {
      "argv": [
        "/target/debug/build/serde_json-f663e98440021490/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 52064,
      "build_script_target_dir": "serde_json-f663e98440021490",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/serde_json-f663e98440021490/build-script-build",
      "pid": 52064,
      "ppid": 51532,
      "root_cargo_pid": 51532,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
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
    },
    {
      "crate": "serde_json",
      "cwd": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "event_id": "bsrun:769c25bda3f61aad:b53fe9c00a356d6f:135b23063d020806",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/serde_json-f663e98440021490/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
      "out_dir": "/target/debug/build/serde_json-f663e98440021490/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
      "success": true,
      "target": null,
      "version": "1.0.140",
      "_owner": {
        "crate": "serde_json",
        "version": "1.0.140",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140#serde_json@1.0.140",
        "manifest_dir": "/tmp/crate-build-ppc64le-vz1zyw6i/src/serde_json-1.0.140",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
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
