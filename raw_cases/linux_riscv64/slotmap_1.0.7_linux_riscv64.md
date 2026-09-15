# `slotmap` `1.0.7`

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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
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
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4",
    "/target/debug/build/slotmap-9cd0fd3344a99352",
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
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-154171-1783993095065147188.map",
  "pid": 154171,
  "ppid": 154144,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-154171-1783993095065147188.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "workspace_root": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@0.7.15",
      "name": "aho-corasick",
      "version": "0.7.15",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.7.15/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.7.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#byteorder@1.4.3",
      "name": "byteorder",
      "version": "1.4.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.4.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.4.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@0.1.10",
      "name": "cfg-if",
      "version": "0.1.10",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-0.1.10/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-0.1.10"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#env_logger@0.7.1",
      "name": "env_logger",
      "version": "0.7.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.7.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.7.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fxhash@0.2.1",
      "name": "fxhash",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fxhash-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fxhash-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.1.16",
      "name": "getrandom",
      "version": "0.1.16",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.1.16/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.1.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@0.4.7",
      "name": "itoa",
      "version": "0.4.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-0.4.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-0.4.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.4.0",
      "name": "lazy_static",
      "version": "1.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.82",
      "name": "libc",
      "version": "0.2.82",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.82/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.82"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.11",
      "name": "log",
      "version": "0.4.11",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.11/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.3.4",
      "name": "memchr",
      "version": "2.3.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.3.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.3.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.10",
      "name": "ppv-lite86",
      "version": "0.2.10",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.10/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.10"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.24",
      "name": "proc-macro2",
      "version": "1.0.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quickcheck@0.9.2",
      "name": "quickcheck",
      "version": "0.9.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quickcheck-0.9.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quickcheck-0.9.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.8",
      "name": "quote",
      "version": "1.0.8",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.8/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.7.3",
      "name": "rand",
      "version": "0.7.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.7.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.7.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.2.2",
      "name": "rand_chacha",
      "version": "0.2.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.2.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.2.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.5.1",
      "name": "rand_core",
      "version": "0.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.5.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_hc@0.2.0",
      "name": "rand_hc",
      "version": "0.2.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_hc-0.2.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_hc-0.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.4.3",
      "name": "regex",
      "version": "1.4.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.4.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.4.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.6.22",
      "name": "regex-syntax",
      "version": "0.6.22",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.6.22/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.6.22"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.5",
      "name": "ryu",
      "version": "1.0.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.118",
      "name": "serde",
      "version": "1.0.118",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.118/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.118"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.118",
      "name": "serde_derive",
      "version": "1.0.118",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.118/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.118"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.61",
      "name": "serde_json",
      "version": "1.0.61",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.61/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.61"
    },
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
      "name": "slotmap",
      "version": "1.0.7",
      "manifest_path": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@1.0.58",
      "name": "syn",
      "version": "1.0.58",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.58/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.58"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#thread_local@1.1.0",
      "name": "thread_local",
      "version": "1.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-1.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-xid@0.2.1",
      "name": "unicode-xid",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.3",
      "name": "version_check",
      "version": "0.9.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.9.0+wasi-snapshot-preview1",
      "name": "wasi",
      "version": "0.9.0+wasi-snapshot-preview1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.9.0+wasi-snapshot-preview1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.9.0+wasi-snapshot-preview1"
    }
  ],
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "exit_code": 0,
  "kind": "exec",
  "pid": 154171,
  "ppid": 154144,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "event_id": "used:cc:47e4d1218f5ea2a8:386d42acc56d2cea:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
  "pid": 154171,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "event_id": "used:cc:47e4d1218f5ea2a8:2ded3811d8dec623:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
  "pid": 154171,
  "sha256": "dea6dcaed930d777cc5f99c50b1a41be9c3aeb6cbc321aec1db79f2ffffec160",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "event_id": "used:cc:47e4d1218f5ea2a8:4b20b30bc38537f7:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
  "pid": 154171,
  "sha256": "c8c7368c6698245bd85e04b50f4e74916897f022c35ce52a5ac1c61b6de5c0b7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "event_id": "used:cc:47e4d1218f5ea2a8:4bc316c3e46749f5:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
  "pid": 154171,
  "sha256": "b9c97d8e703e9ed61a64869bae4936c3f82e07c364a04ae891cac7f0c36f099d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "event_id": "used:cc:47e4d1218f5ea2a8:0d4a7bb039a9b590:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
  "pid": 154171,
  "sha256": "c8f8714082ffda15e74f9c0ef582d1720d0c3b3b1ae96fbba3c4a0b2f505200a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "event_id": "used:cc:47e4d1218f5ea2a8:3c4fc32a0fb9bc69:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
  "pid": 154171,
  "sha256": "f8d51f1c59be4af46a4950929bc728f50062a02ed9113b5126b192c6dffc502e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "event_id": "used:cc:47e4d1218f5ea2a8:7338e5158544e35f:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
  "pid": 154171,
  "sha256": "c764875bcff97ee3d3d921902251fd5e89f69a06d7acc84e5f2b37bfbbd7e919",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "event_id": "used:cc:47e4d1218f5ea2a8:b1d8e2dfeb9e4333:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
  "pid": 154171,
  "sha256": "895401de1b5266e41d1766c69928df3229a938b21509b0be3b8542aad0d7ccb1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "event_id": "used:cc:47e4d1218f5ea2a8:826fc52410fa9286:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
  "pid": 154171,
  "sha256": "53420bd557aaea032308b14a4f9cdeb5498ed41f91c12f467e983e80765f4c22",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "event_id": "used:cc:47e4d1218f5ea2a8:806c34ec40eb7e52:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
  "pid": 154171,
  "sha256": "19e4a3cc62f0b57413eb48adfdf7b9c6c64181801a9976c8a83f99accc17b5c4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
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
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "context_path": "/tmp/native-trace-152560-1783993089904/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-152560-1783993089904/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 154171,
  "ppid": 154144,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4",
    "/target/debug/build/slotmap-9cd0fd3344a99352",
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
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-154171-1783993095065147188.map",
  "pid": 154171,
  "ppid": 154144,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-154171-1783993095065147188.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

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

#### Record 17

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 821,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 823,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": " /usr/bin/docker-init --version\n9.455   docker           155573 155250   0 /usr/bin/docker info -f {{.SecurityOptions}}\n9.467   runc             155588 1599     0 /usr/bin/runc --version\n9.469   docker-init      155594 1599     0 /usr/bin/docker-init --version\n9.473   rustup           155595 155225   0 /home/xmoe/.cargo/bin/rustup toolchain list\n9.477   rustup           155604 155224   0 /home/xmoe/.cargo/bin/rustup toolchain list\n9.479   rustup           155605 155225   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n9.483   rustup           155622 155224   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n9.493   rustup           155631 155250   0 /home/xmoe/.cargo/bin/rustup toolchain list\n9.499   rustup           155640 155250   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n9.503   rustup           155649 155225   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n9.506   rustup           155658 155224   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n9.525   rustup           155667 155250   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n9.527   uname            155668 155225   0 /usr/bin/uname -r\n9.530   uname            155677 155224   0 /usr/bin/uname -r\n9.543   docker           155678 155225   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n9.548   docker           155684 155224   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n9.550   uname            155685 155250   0 /usr/bin/uname -r\n9.570   docker           155700 155250   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n9.588   systemd-sysctl   155724 155722   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7e9cf7b --prefix=/net/ipv4/neigh/veth7e9cf7b --prefix=/net/ipv6/conf/veth7e9cf7b --prefix=/net/ipv6/neigh/veth7e9cf7b\n9.590   systemd-sysctl   155725 155723   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha489837 --prefix=/net/ipv4/neigh/vetha489837 --prefix=/net/ipv6/conf/vetha489837 --prefix=/net/ipv6/neigh/vetha489837\n9.594   systemd-sysctl   155728 155726   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda9a202 --prefix=/net/ipv4/neigh/vethda9a202 --prefix=/net/ipv6/conf/vethda9a202 --prefix=/net/ipv6/neigh/vethda9a202\n9.594   systemd-sysctl   155729 155727   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5716b6b --prefix=/net/ipv4/neigh/veth5716b6b --prefix=/net/ipv6/conf/veth5716b6b --prefix=/net/ipv6/neigh/veth5716b6b\n9.647   systemd-sysctl   155761 155732   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4f94b4 --prefix=/net/ipv4/neigh/vethf4f94b4 --prefix=/net/ipv6/conf/vethf4f94b4 --prefix=/net/ipv6/neigh/vethf4f94b4\n9.648   systemd-sysctl   155762 155739   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8c45214 --prefix=/net/ipv4/neigh/veth8c45214 --prefix=/net/ipv6/conf/veth8c45214 --prefix=/net/ipv6/neigh/veth8c45214\n9.707   containerd-shim  155763 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 start\n9.710   containerd-shim  155769 155763   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 -address /var/run/docker/containerd/containerd.sock\n9.714   runc             155779 155769   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731\n9.719   exe              155788 155779   0 /proc/self/exe init\n9.758   exe              155796 155779   0 /proc/1599/exe -exec-root=/var/run/docker e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 d7da31e8f8e1\n9.776   exe              155804 1599     0 /proc/self/exe /var/run/docker/netns/3a348ec5d0f1 all false\n9.810   containerd-shim  155820 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb start\n9.811   containerd-shim  155824 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea start\n9.813   containerd-shim  155832 155820   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb -address /var/run/docker/containerd/containerd.sock\n9.814   containerd-shim  155839 155824   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea -address /var/run/docker/containerd/containerd.sock\n9.817   runc             155855 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb\n9.817   runc             155856 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea\n9.823   exe              155871 155855   0 /proc/self/exe init\n9.823   exe              155872 155856   0 /proc/self/exe init\n9.825   runc             155875 155769   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --log-format json --systemd-cgroup start e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731\n9.830   sh               155790 155769   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n9.831   cargo            155882 155790   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n9.842   cargo-native-tr  155882 155790   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n9.846   cargo            155897 155882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n9.851   exe              155898 155856   0 /proc/1599/exe -exec-root=/var/run/docker 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea d7da31e8f8e1\n9.852   exe              155899 155855   0 /proc/1599/exe -exec-root=/var/run/docker d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb d7da31e8f8e1\n9.858   rustc            155910 155897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.870   exe              155916 1599     0 /proc/self/exe /var/run/docker/netns/20e6cea9bf06 all false\n9.870   rustc            155915 155897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n9.872   exe              155917 1599     0 /proc/self/exe /var/run/docker/netns/4ce422236531 all false\n9.893   execsnoop        155950 155882   0 /usr/local/bin/execsnoop -t\n9.894   python3          155950 155882   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n9.938   runc             155954 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup start d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb\n9.938   runc             155955 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup start 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea\n9.943   sh               155891 155832   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n9.944   sh               155884 155839   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n9.945   cargo            155965 155891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n9.945   cargo            155966 155884   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n9.956   cargo-native-tr  155966 155884   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n9.958   cargo-native-tr  155965 155891   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n9.960   cargo            155967 155966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n9.961   cargo            155968 155965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n9.971   rustc            155969 155967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.971   rustc            155970 155968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.982   rustc            155973 155967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n9.983   rustc            155974 155968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n10.008  execsnoop        155981 155965   0 /usr/local/bin/execsnoop -t\n10.009  python3          155981 155965   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n10.010  execsnoop        155984 155966   0 /usr/local/bin/execsnoop -t\n10.010  python3          155984 155966   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n10.198  16               155987 1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n10.213  frpc             155987 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n11.914  cargo            155993 155965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n11.916  cargo            155994 155966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n11.928  rustc            155995 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.929  rustc            155996 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.954  rustc            156009 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"defmt-03\", \"mpmc_large\", \"portable-atomic\", \"portable-atomic-critical-section\", \"portable-atomic-unsafe-ass -C metadata=0bcf272fd4a41228 ...\n11.954  rustc            156010 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n11.955  rustc            156011 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name byteorder --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"i128\", \"std\")) -C metadata=c48b90dfbbda9f5e ...\n11.958  rustc            156012 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name stable_deref_trait --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stable_deref_trait-1.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"default\", \"std\")) -C metadata=142658315e27326b ...\n12.035  rustc            156052 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hash32 --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hash32-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=871b075c5f9c75b5 ...\n12.061  cc               156086 156009   0 /tmp/native-trace-155966-1783993104406/shims/cc -m64 /target/debug/build/heapless-1640e7d816e37021/rustcB5MYOH/symbols.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.003xu6mngsx05pt7soakh8kmx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.01vzefae9ykg3tha98hqn4qjd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.03q26do3xj4reflzp4ujkhtou.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0rqdwaxd1mao1yhu1t1qhncts.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0xa7kgbuw0i07l44ujmiazs1v.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.1ic2mqya3v3laouyh8018e7yu.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.21d9n7nvjp9whhlnjfwrzcaip.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2chmhzmce29un2p5aqvsy15jh.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2h4lopnp3woikeonplzmhc0nv.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2mju1ukg99b0yv1s0g0opq28d.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2n6t2sx4jts63nobe1ju4xofx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rhokkseltpqc9andmx6u2r2w.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rw4yme7h7aehc6u1ma26fxum.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2zvb2xpkrh4onudn3rzvmu7k4.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3k1vkeh97ivuanpaqm9wnbm35.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mohzrrezerp65vdqoaar8xtd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mon2525yms8rau8qxu3n5jd4.1uwodqe.rcgu.o ...\n12.063  cc               156087 156086   0 /usr/bin/cc -m64 /target/debug/build/heapless-1640e7d816e37021/rustcB5MYOH/symbols.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.003xu6mngsx05pt7soakh8kmx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.01vzefae9ykg3tha98hqn4qjd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.03q26do3xj4reflzp4ujkhtou.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0rqdwaxd1mao1yhu1t1qhncts.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0xa7kgbuw0i07l44ujmiazs1v.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.1ic2mqya3v3laouyh8018e7yu.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.21d9n7nvjp9whhlnjfwrzcaip.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2chmhzmce29un2p5aqvsy15jh.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2h4lopnp3woikeonplzmhc0nv.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2mju1ukg99b0yv1s0g0opq28d.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2n6t2sx4jts63nobe1ju4xofx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rhokkseltpqc9andmx6u2r2w.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rw4yme7h7aehc6u1ma26fxum.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2zvb2xpkrh4onudn3rzvmu7k4.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3k1vkeh97ivuanpaqm9wnbm35.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mohzrrezerp65vdqoaar8xtd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mon2525yms8rau8qxu3n5jd4.1uwodqe.rcgu.o ...\n12.067  collect2         156088 156087   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.069  ld.lld           156091 156088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021 ...\n12.071  rust-lld         156091 156088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n12.082  runc             156095 146687   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 --log-format json --systemd-cgroup kill --all 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c 9\n12.103  runc             156120 146687   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 --log-format json --systemd-cgroup delete 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c\n12.131  build-script-bu  156129 155994   0 /target/debug/build/heapless-1640e7d816e37021/build-script-build\n12.137  rustc            156131 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name heapless --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"defmt-03\", \"mpmc_large\", \"portable-atomic\", \"portable-atomic-critical-section\", \"portable-atomic-unsafe-ass -C metadata=81506217a3a7e12c ...\n12.154  cargo            156136 155882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n12.168  rustc            156137 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n12.179  rustc            156142 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=8eab25d199e7deb9 ...\n12.188  rustc            156145 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n12.209  cc               156159 156142   0 /tmp/native-trace-155965-1783993104408/shims/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcsi6iI5/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.0co4w98.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n12.210  cc               156160 156159   0 /usr/bin/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcsi6iI5/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.0co4w98.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n12.213  collect2         156161 156160   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.215  ld.lld           156162 156161   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b ...\n12.216  rust-lld         156162 156161   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n12.259  build-script-bu  156180 155993   0 /target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build\n12.261  rustc            156181 156180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n12.272  rustc            156183 156180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_ae266a08b08eb5bb_0 --crate-type=lib --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/fs-err-6e7f7f43f71799c8/out --emit=llvm-ir --target powerpc64le-unknown-linux-gnu -\n12.293  containerd-shim  156194 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 delete\n12.295  rustc            156193 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_err --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=ea980410505747aa ...\n12.296  runc             156201 156194   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434 --log-format json delete --force 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c\n12.331  systemd-sysctl   156212 155732   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth649a077 --prefix=/net/ipv4/neigh/veth649a077 --prefix=/net/ipv6/conf/veth649a077 --prefix=/net/ipv6/neigh/veth649a077\n12.391  rustc            156216 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=8eab25d199e7deb9 ...\n12.423  cc               156242 156216   0 /tmp/native-trace-155882-1783993104292/shims/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n12.425  cc               156249 156242   0 \n12.427  collect2         156253 156249   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.429  ld.lld           156256 156253   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b ...\n12.431  rust-lld         156256 156253   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n12.471  build-script-bu  156298 156136   0 /target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build\n12.473  rustc            156299 156298   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n12.485  rustc            156301 156298   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_77a383603c224a07_0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/fs-err-d223f2b3d73c7254/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n12.504  rustc            156309 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_err --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=e5fa82910511c4ea ...\n12.804  runc             156363 150150   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d --log-format json --systemd-cgroup kill --all 9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d611c2 9\n12.822  runc             156369 150150   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d --log-format json --systemd-cgroup delete 9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d611c2\n12.999  containerd-shim  156375 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d611c2 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d delete\n13.002  runc             156382 156375   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d611c --log-format json delete --force 9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d611c2\n13.044  sh               156389 155732   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth5ce6651\n13.046  ethtool          156390 156389   0 /usr/sbin/ethtool -i veth5ce6651\n13.046  sed              156391 156389   0 /usr/bin/sed -n s/^driver: //p\n13.051  systemd-sysctl   156394 155732   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5ce6651 --prefix=/net/ipv4/neigh/veth5ce6651 --prefix=/net/ipv6/conf/veth5ce6651 --prefix=/net/ipv6/neigh/veth5ce6651\n13.373  sh               156395 2147557   0 /bin/sh -c which ps\n13.375  which            156395 2147557   0 /usr/bin/which ps\n13.376  sh               156396 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.377  ps               156396 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.403  sh               156397 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n13.405  cpuUsage.sh      156397 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n13.406  sed              156398 156397   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n13.408  cat              156399 156397   0 /usr/bin/cat /proc/2240539/stat\n13.409  cat              156400 156397   0 /usr/bin/cat /proc/4193716/stat\n13.410  sleep            156401 156397   0 /usr/bin/sleep 1\n14.413  sed              156402 156397   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.416  cat              156403 156397   0 /usr/bin/cat /proc/2240539/stat\n14.419  cat              156405 156397   0 /usr/bin/cat /proc/4193716/stat\n15.708  runc             156407 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1103544788 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n15.714  exe              156414 156407   0 /proc/self/exe init\n15.737  curl             156417 156407   0 /usr/bin/curl -f http://localhost:9091/healthz\n16.204  runc             156425 150300   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c --log-format json --systemd-cgroup kill --all 6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c4a18e 9\n16.223  runc             156431 150300   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c --log-format json --systemd-cgroup delete 6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c4a18e\n16.362  cross            156437 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n16.363  cross            156438 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n16.364  rustc            156443 156437   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.364  rustc            156444 156438   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.371  rustc            156443 156437   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.371  rustc            156444 156438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.385  rustc            156467 156438   0 /home/xmoe/.cargo/bin/rustc -vV\n16.385  rustc            156468 156437   0 /home/xmoe/.cargo/bin/rustc -vV\n16.391  rustc            156467 156438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.391  rustc            156468 156437   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.403  cargo            156487 156437   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.403  cargo            156488 156438   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.406  containerd-shim  156494 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c4a18e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c delete\n16.410  runc             156513 156494   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c4a18 --log-format json delete --force 6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c4a18e\n16.410  cargo            156487 156437   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.410  cargo            156488 156438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.424  rustc            156519 156487   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.425  rustc            156520 156488   0 \n16.437  rustc            156523 156487   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.439  rustc            156524 156488   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.442  runc             156525 150673   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472 --log-format json --systemd-cgroup kill --all 92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472b1c2b 9\n16.451  sh               156540 156531   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethc9b6a23\n16.452  rustc            156541 156487   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.453  rustc            156542 156488   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.453  ethtool          156543 156540   0 /usr/sbin/ethtool -i vethc9b6a23\n16.453  sed              156544 156540   0 /usr/bin/sed -n s/^driver: //p\n16.461  systemd-sysctl   156547 156531   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc9b6a23 --prefix=/net/ipv4/neigh/vethc9b6a23 --prefix=/net/ipv6/conf/vethc9b6a23 --prefix=/net/ipv6/neigh/vethc9b6a23\n16.461  runc             156548 150673   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472 --log-format json --systemd-cgroup delete 92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472b1c2b\n16.655  containerd-shim  156564 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472b1c2b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472 delete\n16.658  runc             156571 156564   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472b1c2 --log-format json delete --force 92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472b1c2b\n16.700  systemd-sysctl   156576 156561   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb8b42dc --prefix=/net/ipv4/neigh/vethb8b42dc --prefix=/net/ipv6/conf/vethb8b42dc --prefix=/net/ipv6/neigh/vethb8b42dc\n16.771  rustc            156578 156488   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.793  rustc            156580 156487   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.824  rustc            156582 156438   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.826  rustc            156583 156437   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.832  rustc            156583 156437   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.832  rustc            156582 156438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.847  docker           156606 156438   0 /usr/bin/docker --help\n16.848  docker           156607 156437   0 /usr/bin/docker --help\n16.863  docker           156628 156438   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.864  docker           156629 156437   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.877  runc             156650 1599     0 /usr/bin/runc --version\n16.877  runc             156651 1599     0 /usr/bin/runc --version\n16.880  docker-init      156662 1599     0 /usr/bin/docker-init --version\n16.881  docker-init      156663 1599     0 /usr/bin/docker-init --version\n16.882  docker           156664 156437   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.883  docker           156665 156438   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.897  runc             156685 1599     0 /usr/bin/runc --version\n16.897  runc             156686 1599     0 /usr/bin/runc --version\n16.900  docker-init      156697 1599     0 /usr/bin/docker-init --version\n16.901  docker-init      156698 1599     0 /usr/bin/docker-init --version\n16.928  rustup           156699 156438   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.931  rustup           156700 156437   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.936  rustup           156717 156438   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.938  rustup           156718 156437   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.966  rustup           156735 156438   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.969  rustup           156743 156437   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.997  uname            156753 156438   0 /usr/bin/uname -r\n17.002  uname            156754 156437   0 /usr/bin/uname -r\n17.020  docker           156755 156438   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.025  docker           156761 156437   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.070  systemd-sysctl   156782 156561   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5fa07e5 --prefix=/net/ipv4/neigh/veth5fa07e5 --prefix=/net/ipv6/conf/veth5fa07e5 --prefix=/net/ipv6/neigh/veth5fa07e5\n17.071  systemd-sysctl   156783 156531   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2a208c9 --prefix=/net/ipv4/neigh/veth2a208c9 --prefix=/net/ipv6/conf/veth2a208c9 --prefix=/net/ipv6/neigh/veth2a208c9\n17.073  runc             156785 152087   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f69 --log-format json --systemd-cgroup kill --all 9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f697a1e0 9\n17.076  systemd-sysctl   156792 156577   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2cd7f24 --prefix=/net/ipv4/neigh/veth2cd7f24 --prefix=/net/ipv6/conf/veth2cd7f24 --prefix=/net/ipv6/neigh/veth2cd7f24\n17.078  systemd-sysctl   156793 156786   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethcc45254 --prefix=/net/ipv4/neigh/vethcc45254 --prefix=/net/ipv6/conf/vethcc45254 --prefix=/net/ipv6/neigh/vethcc45254\n17.083  runc             156804 152087   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f69 --log-format json --systemd-cgroup delete 9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f697a1e0\n17.095  containerd-shim  156830 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02e16b1 start\n17.099  containerd-shim  156838 156830   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02e16b1 -address /var/run/docker/containerd/containerd.sock\n17.105  runc             156847 156838   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02 ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02e16b1\n17.112  exe              156855 156847   0 /proc/self/exe init\n17.143  containerd-shim  156856 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465ec830 start\n17.147  containerd-shim  156870 156856   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465ec830 -address /var/run/docker/containerd/containerd.sock\n17.152  runc             156880 156870   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465 7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465ec830\n17.159  exe              156887 156880   0 /proc/self/exe init\n17.181  exe              156890 156847   0 /proc/1599/exe -exec-root=/var/run/docker ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02e16b1 d7da31e8f8e1\n17.201  exe              156905 156880   0 /proc/1599/exe -exec-root=/var/run/docker 7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465ec830 d7da31e8f8e1\n17.204  exe              156912 1599     0 /proc/self/exe /var/run/docker/netns/a2b1bbae72bb all false\n17.225  exe              156933 1599     0 /proc/self/exe /var/run/docker/netns/d95974ddb7ff all false\n17.254  runc             156954 156838   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02 --log-format json --systemd-cgroup start ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02e16b1\n17.261  sh               156861 156838   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.262  cargo            156960 156861   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.271  runc             156961 156870   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465 --log-format json --systemd-cgroup start 7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465ec830\n17.275  cargo-native-tr  156960 156861   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.277  sh               156891 156870   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.278  cargo            156967 156891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.279  cargo            156968 156960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.289  containerd-shim  156969 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f697a1e0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f69 delete\n17.290  cargo-native-tr  156967 156891   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.290  rustc            156970 156968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.292  runc             156977 156969   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f697a1e --log-format json delete --force 9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f697a1e0\n17.292  runc             156978 150954   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee0 --log-format json --systemd-cgroup kill --all 7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee04ab33 9\n17.293  cargo            156982 156967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.303  rustc            156990 156968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.305  rustc            156992 156982   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.309  runc             156994 150954   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee0 --log-format json --systemd-cgroup delete 7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee04ab33\n17.316  rustc            157004 156982   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.321  systemd-sysctl   157005 156805   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7ae9ddd --prefix=/net/ipv4/neigh/veth7ae9ddd --prefix=/net/ipv6/conf/veth7ae9ddd --prefix=/net/ipv6/neigh/veth7ae9ddd\n17.325  execsnoop        157009 156960   0 /usr/local/bin/execsnoop -t\n17.326  python3          157009 156960   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.337  execsnoop        157012 156967   0 /usr/local/bin/execsnoop -t\n17.338  python3          157012 156967   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.514  containerd-shim  157015 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee04ab33 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee0 delete\n17.516  runc             157021 157015   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee04ab3 --log-format json delete --force 7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee04ab33\n17.556  systemd-sysctl   157027 156805   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth54b6187 --prefix=/net/ipv4/neigh/veth54b6187 --prefix=/net/ipv6/conf/veth54b6187 --prefix=/net/ipv6/neigh/veth54b6187\n17.685  runc             157028 152612   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279d --log-format json --systemd-cgroup kill --all e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279df499b 9\n17.702  runc             157035 152612   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279d --log-format json --systemd-cgroup delete e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279df499b\n17.891  containerd-shim  157041 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279df499b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279d delete\n17.894  runc             157048 157041   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279df499 --log-format json delete --force e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279df499b\n17.933  systemd-sysctl   157053 156805   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth27c233c --prefix=/net/ipv4/neigh/veth27c233c --prefix=/net/ipv6/conf/veth27c233c --prefix=/net/ipv6/neigh/veth27c233c\n18.063  git              157054 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n18.366  runc             157055 152236   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5ffc855b4d665d1fd100d15e8cd446e18d671598fd662201b45cb191d3e --log-format json --systemd-cgroup kill --all 5ffc855b4d665d1fd100d15e8cd446e18d671598fd662201b45cb191d3e60165 9\n18.373  sh               157061 2147557   0 /bin/sh -c which ps\n18.374  which            157061 2147557   0 /usr/bin/which ps\n18.375  sh               157062 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.376  ps               157062 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.383  runc             157064 152236   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5ffc855b4d665d1fd100d15e8cd446e18d671598fd662201b45cb191d3e --log-format json --systemd-cgroup delete 5ffc855b4d665d1fd100d15e8cd446e18d671598fd662201b45cb191d3e60165\n18.387  git              157063 2235138   0 /usr/bin/git config --get commit.template\n18.401  sh               157071 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.402  cpuUsage.sh      157071 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.403  sed              157072 157071   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.404  git              157070 2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n18.405  cat              157073 157071   0 /usr/bin/cat /proc/2240539/stat\n18.406  cat              157074 157071   0 /usr/bin/cat /proc/4193716/stat\n18.407  sleep            157075 157071   0 /usr/bin/sleep 1\n18.421  git              157076 2235138   0 /usr/bin/git status -z -uall\n"
}
```

#### Record 18

```json
{
  "argv": [
    "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 154226,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build",
  "pid": 154226,
  "ppid": 153897,
  "root_cargo_pid": 153897,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_build_script_out_dir": "/target/debug/build/slotmap-9cd0fd3344a99352/out"
}
```

#### Record 19

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 154226,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 154227,
  "ppid": 154226,
  "root_cargo_pid": 153897,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_build_script_out_dir": "/target/debug/build/slotmap-9cd0fd3344a99352/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 20

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 154226,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 154230,
  "ppid": 154226,
  "root_cargo_pid": 153897,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_build_script_out_dir": "/target/debug/build/slotmap-9cd0fd3344a99352/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 21

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 154226,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 154237,
  "ppid": 154226,
  "root_cargo_pid": 153897,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_build_script_out_dir": "/target/debug/build/slotmap-9cd0fd3344a99352/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 22

```json
{
  "crate": "slotmap",
  "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "event_id": "bsrun:9c6433f88cb42ff8:31fc1c25b134e6d5:0b48ffbf0383fa98",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
  "out_dir": "/target/debug/build/slotmap-9cd0fd3344a99352/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
  "success": true,
  "target": null,
  "version": "1.0.7",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
    "source": "cwd_prefix"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 154226,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 154227,
  "ppid": 154226,
  "root_cargo_pid": 153897,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 24

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 154226,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 154230,
  "ppid": 154226,
  "root_cargo_pid": 153897,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 25

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 154226,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 154237,
  "ppid": 154226,
  "root_cargo_pid": 153897,
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
  "time": "2026-07-14T01:38:33.219833+00:00",
  "crate": "slotmap",
  "version": "1.0.7",
  "architecture": "riscv64",
  "duration_seconds": 28.541894824244082,
  "trace_record_count": 22,
  "trace_owner_summary": {
    "owner_package_count": 32,
    "owner_packages": [
      {
        "crate": "wasi",
        "version": "0.9.0+wasi-snapshot-preview1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.9.0+wasi-snapshot-preview1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.9.0+wasi-snapshot-preview1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.9.0+wasi-snapshot-preview1/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.118",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.118",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.118",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.118/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "0.7.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@0.7.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.7.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.7.15/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.6.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.6.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.6.22",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.6.22/Cargo.toml"
      },
      {
        "crate": "version_check",
        "version": "0.9.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.3/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.24",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.24",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.24/Cargo.toml"
      },
      {
        "crate": "thread_local",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#thread_local@1.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-1.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-1.1.0/Cargo.toml"
      },
      {
        "crate": "lazy_static",
        "version": "1.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.4.0/Cargo.toml"
      },
      {
        "crate": "ppv-lite86",
        "version": "0.2.10",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.10",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.10",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.10/Cargo.toml"
      },
      {
        "crate": "rand_chacha",
        "version": "0.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.2.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.2.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.2.2/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.61",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.61",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.61",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.61/Cargo.toml"
      },
      {
        "crate": "unicode-xid",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-xid@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.2.1/Cargo.toml"
      },
      {
        "crate": "env_logger",
        "version": "0.7.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#env_logger@0.7.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.7.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.7.1/Cargo.toml"
      },
      {
        "crate": "getrandom",
        "version": "0.1.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.1.16",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.1.16",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.1.16/Cargo.toml"
      },
      {
        "crate": "quickcheck",
        "version": "0.9.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quickcheck@0.9.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quickcheck-0.9.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quickcheck-0.9.2/Cargo.toml"
      },
      {
        "crate": "byteorder",
        "version": "1.4.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#byteorder@1.4.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.4.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.4.3/Cargo.toml"
      },
      {
        "crate": "rand_core",
        "version": "0.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.5.1/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "0.1.10",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@0.1.10",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-0.1.10",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-0.1.10/Cargo.toml"
      },
      {
        "crate": "rand_hc",
        "version": "0.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_hc@0.2.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_hc-0.2.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_hc-0.2.0/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.118",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.118",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.118",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.118/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml"
      },
      {
        "crate": "fxhash",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fxhash@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fxhash-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fxhash-0.2.1/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.3.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.3.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.3.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.3.4/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.82",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.82",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.82",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.82/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.8",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.8/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.4.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.4.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.4.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.4.3/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "0.4.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@0.4.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-0.4.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-0.4.7/Cargo.toml"
      },
      {
        "crate": "log",
        "version": "0.4.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.11/Cargo.toml"
      },
      {
        "crate": "rand",
        "version": "0.7.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.7.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.7.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.7.3/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "1.0.58",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@1.0.58",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.58",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.58/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.5/Cargo.toml"
      },
      {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "manifest_path": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7/Cargo.toml"
      }
    ],
    "attributed_event_count": 16,
    "unattributed_event_count": 6,
    "owners": [
      {
        "crate": "slotmap",
        "version": "1.0.7",
        "event_count": 16,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 10,
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
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "workspace_root": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@0.7.15",
          "name": "aho-corasick",
          "version": "0.7.15",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.7.15/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.7.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#byteorder@1.4.3",
          "name": "byteorder",
          "version": "1.4.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.4.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.4.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@0.1.10",
          "name": "cfg-if",
          "version": "0.1.10",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-0.1.10/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-0.1.10"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#env_logger@0.7.1",
          "name": "env_logger",
          "version": "0.7.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.7.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/env_logger-0.7.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fxhash@0.2.1",
          "name": "fxhash",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fxhash-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fxhash-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.1.16",
          "name": "getrandom",
          "version": "0.1.16",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.1.16/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.1.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@0.4.7",
          "name": "itoa",
          "version": "0.4.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-0.4.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-0.4.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.4.0",
          "name": "lazy_static",
          "version": "1.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.82",
          "name": "libc",
          "version": "0.2.82",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.82/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.82"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.11",
          "name": "log",
          "version": "0.4.11",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.11/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.3.4",
          "name": "memchr",
          "version": "2.3.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.3.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.3.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.10",
          "name": "ppv-lite86",
          "version": "0.2.10",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.10/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.10"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.24",
          "name": "proc-macro2",
          "version": "1.0.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quickcheck@0.9.2",
          "name": "quickcheck",
          "version": "0.9.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quickcheck-0.9.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quickcheck-0.9.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.8",
          "name": "quote",
          "version": "1.0.8",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.8/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.7.3",
          "name": "rand",
          "version": "0.7.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.7.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.7.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.2.2",
          "name": "rand_chacha",
          "version": "0.2.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.2.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.2.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.5.1",
          "name": "rand_core",
          "version": "0.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.5.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_hc@0.2.0",
          "name": "rand_hc",
          "version": "0.2.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_hc-0.2.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_hc-0.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.4.3",
          "name": "regex",
          "version": "1.4.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.4.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.4.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.6.22",
          "name": "regex-syntax",
          "version": "0.6.22",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.6.22/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.6.22"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.5",
          "name": "ryu",
          "version": "1.0.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.118",
          "name": "serde",
          "version": "1.0.118",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.118/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.118"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.118",
          "name": "serde_derive",
          "version": "1.0.118",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.118/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.118"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.61",
          "name": "serde_json",
          "version": "1.0.61",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.61/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.61"
        },
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
          "name": "slotmap",
          "version": "1.0.7",
          "manifest_path": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@1.0.58",
          "name": "syn",
          "version": "1.0.58",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.58/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.58"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#thread_local@1.1.0",
          "name": "thread_local",
          "version": "1.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-1.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-xid@0.2.1",
          "name": "unicode-xid",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.3",
          "name": "version_check",
          "version": "0.9.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.9.0+wasi-snapshot-preview1",
          "name": "wasi",
          "version": "0.9.0+wasi-snapshot-preview1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.9.0+wasi-snapshot-preview1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.9.0+wasi-snapshot-preview1"
        }
      ],
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "exit_code": 0,
      "kind": "exec",
      "pid": 154171,
      "ppid": 154144,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "event_id": "used:cc:47e4d1218f5ea2a8:386d42acc56d2cea:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
      "pid": 154171,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "event_id": "used:cc:47e4d1218f5ea2a8:2ded3811d8dec623:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
      "pid": 154171,
      "sha256": "dea6dcaed930d777cc5f99c50b1a41be9c3aeb6cbc321aec1db79f2ffffec160",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "event_id": "used:cc:47e4d1218f5ea2a8:4b20b30bc38537f7:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
      "pid": 154171,
      "sha256": "c8c7368c6698245bd85e04b50f4e74916897f022c35ce52a5ac1c61b6de5c0b7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "event_id": "used:cc:47e4d1218f5ea2a8:4bc316c3e46749f5:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
      "pid": 154171,
      "sha256": "b9c97d8e703e9ed61a64869bae4936c3f82e07c364a04ae891cac7f0c36f099d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "event_id": "used:cc:47e4d1218f5ea2a8:0d4a7bb039a9b590:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
      "pid": 154171,
      "sha256": "c8f8714082ffda15e74f9c0ef582d1720d0c3b3b1ae96fbba3c4a0b2f505200a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "event_id": "used:cc:47e4d1218f5ea2a8:3c4fc32a0fb9bc69:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
      "pid": 154171,
      "sha256": "f8d51f1c59be4af46a4950929bc728f50062a02ed9113b5126b192c6dffc502e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "event_id": "used:cc:47e4d1218f5ea2a8:7338e5158544e35f:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
      "pid": 154171,
      "sha256": "c764875bcff97ee3d3d921902251fd5e89f69a06d7acc84e5f2b37bfbbd7e919",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "event_id": "used:cc:47e4d1218f5ea2a8:b1d8e2dfeb9e4333:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
      "pid": 154171,
      "sha256": "895401de1b5266e41d1766c69928df3229a938b21509b0be3b8542aad0d7ccb1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "event_id": "used:cc:47e4d1218f5ea2a8:826fc52410fa9286:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
      "pid": 154171,
      "sha256": "53420bd557aaea032308b14a4f9cdeb5498ed41f91c12f467e983e80765f4c22",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "event_id": "used:cc:47e4d1218f5ea2a8:806c34ec40eb7e52:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
      "pid": 154171,
      "sha256": "19e4a3cc62f0b57413eb48adfdf7b9c6c64181801a9976c8a83f99accc17b5c4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
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
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "context_path": "/tmp/native-trace-152560-1783993089904/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-152560-1783993089904/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 154171,
      "ppid": 154144,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-3202d02d5d651717.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4",
        "/target/debug/build/slotmap-9cd0fd3344a99352",
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
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcs316V4/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.1mp38bu.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.1mp38bu.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.1mp38bu.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.1mp38bu.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.1mp38bu.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.1mp38bu.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.1mp38bu.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.1mp38bu.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.1mp38bu.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-3202d02d5d651717.rlib(version_check-3202d02d5d651717.version_check.7064f514c6d53823-cgu.4.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-154171-1783993095065147188.map",
      "pid": 154171,
      "ppid": 154144,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-154171-1783993095065147188.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
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
      "parsed_event_count": 821,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 823,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": " /usr/bin/docker-init --version\n9.455   docker           155573 155250   0 /usr/bin/docker info -f {{.SecurityOptions}}\n9.467   runc             155588 1599     0 /usr/bin/runc --version\n9.469   docker-init      155594 1599     0 /usr/bin/docker-init --version\n9.473   rustup           155595 155225   0 /home/xmoe/.cargo/bin/rustup toolchain list\n9.477   rustup           155604 155224   0 /home/xmoe/.cargo/bin/rustup toolchain list\n9.479   rustup           155605 155225   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n9.483   rustup           155622 155224   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n9.493   rustup           155631 155250   0 /home/xmoe/.cargo/bin/rustup toolchain list\n9.499   rustup           155640 155250   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n9.503   rustup           155649 155225   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n9.506   rustup           155658 155224   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n9.525   rustup           155667 155250   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n9.527   uname            155668 155225   0 /usr/bin/uname -r\n9.530   uname            155677 155224   0 /usr/bin/uname -r\n9.543   docker           155678 155225   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n9.548   docker           155684 155224   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n9.550   uname            155685 155250   0 /usr/bin/uname -r\n9.570   docker           155700 155250   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n9.588   systemd-sysctl   155724 155722   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7e9cf7b --prefix=/net/ipv4/neigh/veth7e9cf7b --prefix=/net/ipv6/conf/veth7e9cf7b --prefix=/net/ipv6/neigh/veth7e9cf7b\n9.590   systemd-sysctl   155725 155723   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha489837 --prefix=/net/ipv4/neigh/vetha489837 --prefix=/net/ipv6/conf/vetha489837 --prefix=/net/ipv6/neigh/vetha489837\n9.594   systemd-sysctl   155728 155726   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda9a202 --prefix=/net/ipv4/neigh/vethda9a202 --prefix=/net/ipv6/conf/vethda9a202 --prefix=/net/ipv6/neigh/vethda9a202\n9.594   systemd-sysctl   155729 155727   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5716b6b --prefix=/net/ipv4/neigh/veth5716b6b --prefix=/net/ipv6/conf/veth5716b6b --prefix=/net/ipv6/neigh/veth5716b6b\n9.647   systemd-sysctl   155761 155732   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4f94b4 --prefix=/net/ipv4/neigh/vethf4f94b4 --prefix=/net/ipv6/conf/vethf4f94b4 --prefix=/net/ipv6/neigh/vethf4f94b4\n9.648   systemd-sysctl   155762 155739   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8c45214 --prefix=/net/ipv4/neigh/veth8c45214 --prefix=/net/ipv6/conf/veth8c45214 --prefix=/net/ipv6/neigh/veth8c45214\n9.707   containerd-shim  155763 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 start\n9.710   containerd-shim  155769 155763   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 -address /var/run/docker/containerd/containerd.sock\n9.714   runc             155779 155769   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731\n9.719   exe              155788 155779   0 /proc/self/exe init\n9.758   exe              155796 155779   0 /proc/1599/exe -exec-root=/var/run/docker e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 d7da31e8f8e1\n9.776   exe              155804 1599     0 /proc/self/exe /var/run/docker/netns/3a348ec5d0f1 all false\n9.810   containerd-shim  155820 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb start\n9.811   containerd-shim  155824 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea start\n9.813   containerd-shim  155832 155820   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb -address /var/run/docker/containerd/containerd.sock\n9.814   containerd-shim  155839 155824   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea -address /var/run/docker/containerd/containerd.sock\n9.817   runc             155855 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb\n9.817   runc             155856 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea\n9.823   exe              155871 155855   0 /proc/self/exe init\n9.823   exe              155872 155856   0 /proc/self/exe init\n9.825   runc             155875 155769   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --log-format json --systemd-cgroup start e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731\n9.830   sh               155790 155769   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n9.831   cargo            155882 155790   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n9.842   cargo-native-tr  155882 155790   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n9.846   cargo            155897 155882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n9.851   exe              155898 155856   0 /proc/1599/exe -exec-root=/var/run/docker 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea d7da31e8f8e1\n9.852   exe              155899 155855   0 /proc/1599/exe -exec-root=/var/run/docker d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb d7da31e8f8e1\n9.858   rustc            155910 155897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.870   exe              155916 1599     0 /proc/self/exe /var/run/docker/netns/20e6cea9bf06 all false\n9.870   rustc            155915 155897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n9.872   exe              155917 1599     0 /proc/self/exe /var/run/docker/netns/4ce422236531 all false\n9.893   execsnoop        155950 155882   0 /usr/local/bin/execsnoop -t\n9.894   python3          155950 155882   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n9.938   runc             155954 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup start d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb\n9.938   runc             155955 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup start 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea\n9.943   sh               155891 155832   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n9.944   sh               155884 155839   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n9.945   cargo            155965 155891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n9.945   cargo            155966 155884   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n9.956   cargo-native-tr  155966 155884   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n9.958   cargo-native-tr  155965 155891   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n9.960   cargo            155967 155966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n9.961   cargo            155968 155965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n9.971   rustc            155969 155967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.971   rustc            155970 155968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.982   rustc            155973 155967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n9.983   rustc            155974 155968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n10.008  execsnoop        155981 155965   0 /usr/local/bin/execsnoop -t\n10.009  python3          155981 155965   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n10.010  execsnoop        155984 155966   0 /usr/local/bin/execsnoop -t\n10.010  python3          155984 155966   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n10.198  16               155987 1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n10.213  frpc             155987 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n11.914  cargo            155993 155965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n11.916  cargo            155994 155966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n11.928  rustc            155995 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.929  rustc            155996 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.954  rustc            156009 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"defmt-03\", \"mpmc_large\", \"portable-atomic\", \"portable-atomic-critical-section\", \"portable-atomic-unsafe-ass -C metadata=0bcf272fd4a41228 ...\n11.954  rustc            156010 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n11.955  rustc            156011 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name byteorder --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"i128\", \"std\")) -C metadata=c48b90dfbbda9f5e ...\n11.958  rustc            156012 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name stable_deref_trait --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stable_deref_trait-1.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"default\", \"std\")) -C metadata=142658315e27326b ...\n12.035  rustc            156052 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hash32 --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hash32-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=871b075c5f9c75b5 ...\n12.061  cc               156086 156009   0 /tmp/native-trace-155966-1783993104406/shims/cc -m64 /target/debug/build/heapless-1640e7d816e37021/rustcB5MYOH/symbols.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.003xu6mngsx05pt7soakh8kmx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.01vzefae9ykg3tha98hqn4qjd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.03q26do3xj4reflzp4ujkhtou.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0rqdwaxd1mao1yhu1t1qhncts.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0xa7kgbuw0i07l44ujmiazs1v.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.1ic2mqya3v3laouyh8018e7yu.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.21d9n7nvjp9whhlnjfwrzcaip.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2chmhzmce29un2p5aqvsy15jh.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2h4lopnp3woikeonplzmhc0nv.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2mju1ukg99b0yv1s0g0opq28d.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2n6t2sx4jts63nobe1ju4xofx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rhokkseltpqc9andmx6u2r2w.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rw4yme7h7aehc6u1ma26fxum.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2zvb2xpkrh4onudn3rzvmu7k4.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3k1vkeh97ivuanpaqm9wnbm35.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mohzrrezerp65vdqoaar8xtd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mon2525yms8rau8qxu3n5jd4.1uwodqe.rcgu.o ...\n12.063  cc               156087 156086   0 /usr/bin/cc -m64 /target/debug/build/heapless-1640e7d816e37021/rustcB5MYOH/symbols.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.003xu6mngsx05pt7soakh8kmx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.01vzefae9ykg3tha98hqn4qjd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.03q26do3xj4reflzp4ujkhtou.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0rqdwaxd1mao1yhu1t1qhncts.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0xa7kgbuw0i07l44ujmiazs1v.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.1ic2mqya3v3laouyh8018e7yu.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.21d9n7nvjp9whhlnjfwrzcaip.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2chmhzmce29un2p5aqvsy15jh.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2h4lopnp3woikeonplzmhc0nv.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2mju1ukg99b0yv1s0g0opq28d.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2n6t2sx4jts63nobe1ju4xofx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rhokkseltpqc9andmx6u2r2w.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rw4yme7h7aehc6u1ma26fxum.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2zvb2xpkrh4onudn3rzvmu7k4.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3k1vkeh97ivuanpaqm9wnbm35.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mohzrrezerp65vdqoaar8xtd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mon2525yms8rau8qxu3n5jd4.1uwodqe.rcgu.o ...\n12.067  collect2         156088 156087   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.069  ld.lld           156091 156088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021 ...\n12.071  rust-lld         156091 156088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n12.082  runc             156095 146687   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 --log-format json --systemd-cgroup kill --all 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c 9\n12.103  runc             156120 146687   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 --log-format json --systemd-cgroup delete 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c\n12.131  build-script-bu  156129 155994   0 /target/debug/build/heapless-1640e7d816e37021/build-script-build\n12.137  rustc            156131 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name heapless --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"defmt-03\", \"mpmc_large\", \"portable-atomic\", \"portable-atomic-critical-section\", \"portable-atomic-unsafe-ass -C metadata=81506217a3a7e12c ...\n12.154  cargo            156136 155882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n12.168  rustc            156137 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n12.179  rustc            156142 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=8eab25d199e7deb9 ...\n12.188  rustc            156145 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n12.209  cc               156159 156142   0 /tmp/native-trace-155965-1783993104408/shims/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcsi6iI5/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.0co4w98.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n12.210  cc               156160 156159   0 /usr/bin/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcsi6iI5/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.0co4w98.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n12.213  collect2         156161 156160   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.215  ld.lld           156162 156161   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b ...\n12.216  rust-lld         156162 156161   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n12.259  build-script-bu  156180 155993   0 /target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build\n12.261  rustc            156181 156180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n12.272  rustc            156183 156180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_ae266a08b08eb5bb_0 --crate-type=lib --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/fs-err-6e7f7f43f71799c8/out --emit=llvm-ir --target powerpc64le-unknown-linux-gnu -\n12.293  containerd-shim  156194 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 delete\n12.295  rustc            156193 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_err --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=ea980410505747aa ...\n12.296  runc             156201 156194   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434 --log-format json delete --force 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c\n12.331  systemd-sysctl   156212 155732   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth649a077 --prefix=/net/ipv4/neigh/veth649a077 --prefix=/net/ipv6/conf/veth649a077 --prefix=/net/ipv6/neigh/veth649a077\n12.391  rustc            156216 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=8eab25d199e7deb9 ...\n12.423  cc               156242 156216   0 /tmp/native-trace-155882-1783993104292/shims/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n12.425  cc               156249 156242   0 \n12.427  collect2         156253 156249   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.429  ld.lld           156256 156253   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b ...\n12.431  rust-lld         156256 156253   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n12.471  build-script-bu  156298 156136   0 /target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build\n12.473  rustc            156299 156298   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n12.485  rustc            156301 156298   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_77a383603c224a07_0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/fs-err-d223f2b3d73c7254/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n12.504  rustc            156309 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_err --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=e5fa82910511c4ea ...\n12.804  runc             156363 150150   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d --log-format json --systemd-cgroup kill --all 9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d611c2 9\n12.822  runc             156369 150150   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d --log-format json --systemd-cgroup delete 9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d611c2\n12.999  containerd-shim  156375 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d611c2 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d delete\n13.002  runc             156382 156375   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d611c --log-format json delete --force 9fb2aca261e5f80e54b5d2b11e222345b428d29ff23a8d1d5b63be1db0d611c2\n13.044  sh               156389 155732   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth5ce6651\n13.046  ethtool          156390 156389   0 /usr/sbin/ethtool -i veth5ce6651\n13.046  sed              156391 156389   0 /usr/bin/sed -n s/^driver: //p\n13.051  systemd-sysctl   156394 155732   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5ce6651 --prefix=/net/ipv4/neigh/veth5ce6651 --prefix=/net/ipv6/conf/veth5ce6651 --prefix=/net/ipv6/neigh/veth5ce6651\n13.373  sh               156395 2147557   0 /bin/sh -c which ps\n13.375  which            156395 2147557   0 /usr/bin/which ps\n13.376  sh               156396 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.377  ps               156396 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.403  sh               156397 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n13.405  cpuUsage.sh      156397 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n13.406  sed              156398 156397   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n13.408  cat              156399 156397   0 /usr/bin/cat /proc/2240539/stat\n13.409  cat              156400 156397   0 /usr/bin/cat /proc/4193716/stat\n13.410  sleep            156401 156397   0 /usr/bin/sleep 1\n14.413  sed              156402 156397   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.416  cat              156403 156397   0 /usr/bin/cat /proc/2240539/stat\n14.419  cat              156405 156397   0 /usr/bin/cat /proc/4193716/stat\n15.708  runc             156407 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1103544788 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n15.714  exe              156414 156407   0 /proc/self/exe init\n15.737  curl             156417 156407   0 /usr/bin/curl -f http://localhost:9091/healthz\n16.204  runc             156425 150300   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c --log-format json --systemd-cgroup kill --all 6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c4a18e 9\n16.223  runc             156431 150300   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c --log-format json --systemd-cgroup delete 6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c4a18e\n16.362  cross            156437 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n16.363  cross            156438 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n16.364  rustc            156443 156437   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.364  rustc            156444 156438   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.371  rustc            156443 156437   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.371  rustc            156444 156438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.385  rustc            156467 156438   0 /home/xmoe/.cargo/bin/rustc -vV\n16.385  rustc            156468 156437   0 /home/xmoe/.cargo/bin/rustc -vV\n16.391  rustc            156467 156438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.391  rustc            156468 156437   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.403  cargo            156487 156437   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.403  cargo            156488 156438   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.406  containerd-shim  156494 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c4a18e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c delete\n16.410  runc             156513 156494   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c4a18 --log-format json delete --force 6268c7ed3951ead12def00805736624219310808da6aa817f27cce8781c4a18e\n16.410  cargo            156487 156437   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.410  cargo            156488 156438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.424  rustc            156519 156487   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.425  rustc            156520 156488   0 \n16.437  rustc            156523 156487   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.439  rustc            156524 156488   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.442  runc             156525 150673   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472 --log-format json --systemd-cgroup kill --all 92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472b1c2b 9\n16.451  sh               156540 156531   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethc9b6a23\n16.452  rustc            156541 156487   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.453  rustc            156542 156488   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.453  ethtool          156543 156540   0 /usr/sbin/ethtool -i vethc9b6a23\n16.453  sed              156544 156540   0 /usr/bin/sed -n s/^driver: //p\n16.461  systemd-sysctl   156547 156531   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc9b6a23 --prefix=/net/ipv4/neigh/vethc9b6a23 --prefix=/net/ipv6/conf/vethc9b6a23 --prefix=/net/ipv6/neigh/vethc9b6a23\n16.461  runc             156548 150673   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472 --log-format json --systemd-cgroup delete 92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472b1c2b\n16.655  containerd-shim  156564 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472b1c2b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472 delete\n16.658  runc             156571 156564   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472b1c2 --log-format json delete --force 92779fe121859a9b89bbd97085bff706d72883f6fbc0c08070a05156472b1c2b\n16.700  systemd-sysctl   156576 156561   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb8b42dc --prefix=/net/ipv4/neigh/vethb8b42dc --prefix=/net/ipv6/conf/vethb8b42dc --prefix=/net/ipv6/neigh/vethb8b42dc\n16.771  rustc            156578 156488   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.793  rustc            156580 156487   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.824  rustc            156582 156438   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.826  rustc            156583 156437   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.832  rustc            156583 156437   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.832  rustc            156582 156438   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.847  docker           156606 156438   0 /usr/bin/docker --help\n16.848  docker           156607 156437   0 /usr/bin/docker --help\n16.863  docker           156628 156438   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.864  docker           156629 156437   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.877  runc             156650 1599     0 /usr/bin/runc --version\n16.877  runc             156651 1599     0 /usr/bin/runc --version\n16.880  docker-init      156662 1599     0 /usr/bin/docker-init --version\n16.881  docker-init      156663 1599     0 /usr/bin/docker-init --version\n16.882  docker           156664 156437   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.883  docker           156665 156438   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.897  runc             156685 1599     0 /usr/bin/runc --version\n16.897  runc             156686 1599     0 /usr/bin/runc --version\n16.900  docker-init      156697 1599     0 /usr/bin/docker-init --version\n16.901  docker-init      156698 1599     0 /usr/bin/docker-init --version\n16.928  rustup           156699 156438   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.931  rustup           156700 156437   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.936  rustup           156717 156438   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.938  rustup           156718 156437   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.966  rustup           156735 156438   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.969  rustup           156743 156437   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.997  uname            156753 156438   0 /usr/bin/uname -r\n17.002  uname            156754 156437   0 /usr/bin/uname -r\n17.020  docker           156755 156438   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.025  docker           156761 156437   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.070  systemd-sysctl   156782 156561   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5fa07e5 --prefix=/net/ipv4/neigh/veth5fa07e5 --prefix=/net/ipv6/conf/veth5fa07e5 --prefix=/net/ipv6/neigh/veth5fa07e5\n17.071  systemd-sysctl   156783 156531   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2a208c9 --prefix=/net/ipv4/neigh/veth2a208c9 --prefix=/net/ipv6/conf/veth2a208c9 --prefix=/net/ipv6/neigh/veth2a208c9\n17.073  runc             156785 152087   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f69 --log-format json --systemd-cgroup kill --all 9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f697a1e0 9\n17.076  systemd-sysctl   156792 156577   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2cd7f24 --prefix=/net/ipv4/neigh/veth2cd7f24 --prefix=/net/ipv6/conf/veth2cd7f24 --prefix=/net/ipv6/neigh/veth2cd7f24\n17.078  systemd-sysctl   156793 156786   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethcc45254 --prefix=/net/ipv4/neigh/vethcc45254 --prefix=/net/ipv6/conf/vethcc45254 --prefix=/net/ipv6/neigh/vethcc45254\n17.083  runc             156804 152087   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f69 --log-format json --systemd-cgroup delete 9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f697a1e0\n17.095  containerd-shim  156830 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02e16b1 start\n17.099  containerd-shim  156838 156830   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02e16b1 -address /var/run/docker/containerd/containerd.sock\n17.105  runc             156847 156838   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02 ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02e16b1\n17.112  exe              156855 156847   0 /proc/self/exe init\n17.143  containerd-shim  156856 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465ec830 start\n17.147  containerd-shim  156870 156856   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465ec830 -address /var/run/docker/containerd/containerd.sock\n17.152  runc             156880 156870   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465 7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465ec830\n17.159  exe              156887 156880   0 /proc/self/exe init\n17.181  exe              156890 156847   0 /proc/1599/exe -exec-root=/var/run/docker ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02e16b1 d7da31e8f8e1\n17.201  exe              156905 156880   0 /proc/1599/exe -exec-root=/var/run/docker 7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465ec830 d7da31e8f8e1\n17.204  exe              156912 1599     0 /proc/self/exe /var/run/docker/netns/a2b1bbae72bb all false\n17.225  exe              156933 1599     0 /proc/self/exe /var/run/docker/netns/d95974ddb7ff all false\n17.254  runc             156954 156838   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02 --log-format json --systemd-cgroup start ba5d562784d6707d4f16c6db5497531d67a0c7cb6b5806e38911b5f3d02e16b1\n17.261  sh               156861 156838   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.262  cargo            156960 156861   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.271  runc             156961 156870   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465 --log-format json --systemd-cgroup start 7b52a7ed7a643783dfc85b88db184b66dbae3c4deaa95b37a4a504c9465ec830\n17.275  cargo-native-tr  156960 156861   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.277  sh               156891 156870   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.278  cargo            156967 156891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.279  cargo            156968 156960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.289  containerd-shim  156969 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f697a1e0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f69 delete\n17.290  cargo-native-tr  156967 156891   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.290  rustc            156970 156968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.292  runc             156977 156969   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f697a1e --log-format json delete --force 9cdbdb8a4b261a015fe66021b2fd8d3dfedda2e9c1c60949024deb52f697a1e0\n17.292  runc             156978 150954   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee0 --log-format json --systemd-cgroup kill --all 7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee04ab33 9\n17.293  cargo            156982 156967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.303  rustc            156990 156968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.305  rustc            156992 156982   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.309  runc             156994 150954   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee0 --log-format json --systemd-cgroup delete 7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee04ab33\n17.316  rustc            157004 156982   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.321  systemd-sysctl   157005 156805   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7ae9ddd --prefix=/net/ipv4/neigh/veth7ae9ddd --prefix=/net/ipv6/conf/veth7ae9ddd --prefix=/net/ipv6/neigh/veth7ae9ddd\n17.325  execsnoop        157009 156960   0 /usr/local/bin/execsnoop -t\n17.326  python3          157009 156960   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.337  execsnoop        157012 156967   0 /usr/local/bin/execsnoop -t\n17.338  python3          157012 156967   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.514  containerd-shim  157015 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee04ab33 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee0 delete\n17.516  runc             157021 157015   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee04ab3 --log-format json delete --force 7319afde10d0a0aa1993093dd372bfcb1ca468557d2048e8b42491dcee04ab33\n17.556  systemd-sysctl   157027 156805   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth54b6187 --prefix=/net/ipv4/neigh/veth54b6187 --prefix=/net/ipv6/conf/veth54b6187 --prefix=/net/ipv6/neigh/veth54b6187\n17.685  runc             157028 152612   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279d --log-format json --systemd-cgroup kill --all e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279df499b 9\n17.702  runc             157035 152612   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279d --log-format json --systemd-cgroup delete e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279df499b\n17.891  containerd-shim  157041 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279df499b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279d delete\n17.894  runc             157048 157041   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279df499 --log-format json delete --force e6e2e753a4bdfeb36a24ff82207b0d02e0cb5f858d58e3298ef8134279df499b\n17.933  systemd-sysctl   157053 156805   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth27c233c --prefix=/net/ipv4/neigh/veth27c233c --prefix=/net/ipv6/conf/veth27c233c --prefix=/net/ipv6/neigh/veth27c233c\n18.063  git              157054 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n18.366  runc             157055 152236   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5ffc855b4d665d1fd100d15e8cd446e18d671598fd662201b45cb191d3e --log-format json --systemd-cgroup kill --all 5ffc855b4d665d1fd100d15e8cd446e18d671598fd662201b45cb191d3e60165 9\n18.373  sh               157061 2147557   0 /bin/sh -c which ps\n18.374  which            157061 2147557   0 /usr/bin/which ps\n18.375  sh               157062 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.376  ps               157062 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.383  runc             157064 152236   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5ffc855b4d665d1fd100d15e8cd446e18d671598fd662201b45cb191d3e --log-format json --systemd-cgroup delete 5ffc855b4d665d1fd100d15e8cd446e18d671598fd662201b45cb191d3e60165\n18.387  git              157063 2235138   0 /usr/bin/git config --get commit.template\n18.401  sh               157071 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.402  cpuUsage.sh      157071 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.403  sed              157072 157071   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.404  git              157070 2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n18.405  cat              157073 157071   0 /usr/bin/cat /proc/2240539/stat\n18.406  cat              157074 157071   0 /usr/bin/cat /proc/4193716/stat\n18.407  sleep            157075 157071   0 /usr/bin/sleep 1\n18.421  git              157076 2235138   0 /usr/bin/git status -z -uall\n"
    },
    {
      "argv": [
        "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 154226,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build",
      "pid": 154226,
      "ppid": 153897,
      "root_cargo_pid": 153897,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 154226,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 154227,
      "ppid": 154226,
      "root_cargo_pid": 153897,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 154226,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 154230,
      "ppid": 154226,
      "root_cargo_pid": 153897,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 154226,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 154237,
      "ppid": 154226,
      "root_cargo_pid": 153897,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "slotmap",
      "cwd": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "event_id": "bsrun:9c6433f88cb42ff8:31fc1c25b134e6d5:0b48ffbf0383fa98",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
      "out_dir": "/target/debug/build/slotmap-9cd0fd3344a99352/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
      "success": true,
      "target": null,
      "version": "1.0.7",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-riscv64-p4_ab654/src/slotmap-1.0.7",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 154226,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 154227,
      "ppid": 154226,
      "root_cargo_pid": 153897,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 154226,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 154230,
      "ppid": 154226,
      "root_cargo_pid": 153897,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 154226,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 154237,
      "ppid": 154226,
      "root_cargo_pid": 153897,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 723,
    "crate": "slotmap",
    "version": "1.0.7",
    "crate_id": "72603",
    "version_id": "972639",
    "downloads": 38168092,
    "cumulative_downloads": 81588342967,
    "cumulative_share_of_global": 0.30503997921018894,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "build.rs",
    "build_script_exists": true,
    "package_build_field": null,
    "build_script_reason": "default_build_rs_exists",
    "download_source": "local"
  }
}
```
