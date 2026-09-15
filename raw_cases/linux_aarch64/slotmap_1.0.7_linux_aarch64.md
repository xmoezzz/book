# `slotmap` `1.0.7`

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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx",
    "/target/debug/build/slotmap-9cd0fd3344a99352",
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
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-151652-1783993088991942016.map",
  "pid": 151652,
  "ppid": 151530,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-151652-1783993088991942016.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "workspace_root": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7"
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
      "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
      "name": "slotmap",
      "version": "1.0.7",
      "manifest_path": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7"
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
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "exit_code": 0,
  "kind": "exec",
  "pid": 151652,
  "ppid": 151530,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "event_id": "used:cc:f3e8477555a12adb:b4bcb6bde2261afe:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
  "pid": 151652,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "event_id": "used:cc:f3e8477555a12adb:5b81127e15da9f65:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
  "pid": 151652,
  "sha256": "f3e81bc2c03c5b802d3096189bd58f403463e454317386e32339cd9fcd9045d3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "event_id": "used:cc:f3e8477555a12adb:499e2b28141362a4:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
  "pid": 151652,
  "sha256": "8df2dd9e7878fa6958bacbd264ac90161bb0df333483e42b0bcce9eaa9ac626b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "event_id": "used:cc:f3e8477555a12adb:09e6047fb722a6fa:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
  "pid": 151652,
  "sha256": "1078c6244058e5e602b0969a0cc6a5b467b876533e2c9abc119b5f276a904401",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "event_id": "used:cc:f3e8477555a12adb:c3dc114ab019ca47:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
  "pid": 151652,
  "sha256": "0e130ddcc57638083634963a4fb65b253da1ec94bec0173c096b438ce5f755e3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "event_id": "used:cc:f3e8477555a12adb:b60ab212de479482:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
  "pid": 151652,
  "sha256": "76aa16517bef0f41c80fd4ce0ef1e58dad71dbfbb9d9ff35ede1e5c3d99b5cb9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "event_id": "used:cc:f3e8477555a12adb:162c7cd83597ff0f:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
  "pid": 151652,
  "sha256": "01575e290b2f767ccd2644f1f63e4810fd6a090e22999ad9a56b4a4164e85a34",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "event_id": "used:cc:f3e8477555a12adb:f836a0976d3a5870:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
  "pid": 151652,
  "sha256": "c7f6a519914a011d3bfc1a3078b3b5df0bb010775b0d2b2643cde70754b7fa2b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "event_id": "used:cc:f3e8477555a12adb:31e755c529a01f99:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
  "pid": 151652,
  "sha256": "fa997913a33ac1f8ad61e125c33a5ab771b9d6c494bf733b54de187600cf2e42",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "event_id": "used:cc:f3e8477555a12adb:f1fda6e891156753:3eb20d85f4f09b6f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
  "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
  "pid": 151652,
  "sha256": "19e4a3cc62f0b57413eb48adfdf7b9c6c64181801a9976c8a83f99accc17b5c4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "cargo_pkg_name": "slotmap",
  "cargo_pkg_version": "1.0.7",
  "context_path": "/tmp/native-trace-150515-1783993085902/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-150515-1783993085902/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 151652,
  "ppid": 151530,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
    "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx",
    "/target/debug/build/slotmap-9cd0fd3344a99352",
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
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
      "kind": "object",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-151652-1783993088991942016.map",
  "pid": 151652,
  "ppid": 151530,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-151652-1783993088991942016.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
  "parse_error_count": 1,
  "parsed_event_count": 1188,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1189,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "r/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/88f362f13b0528ed-zstd_decompress.o /tmp/ccRqsFaT.s\n12.900  as               155190 155113   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_fast.o /tmp/ccEd3pLN.s\n12.902  riscv64-linux-g  155189 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.906  abrt-action-cor  155192 155074   0 /usr/libexec/abrt-action-coredump -r\n12.908  cc1              155193 155189   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.910  riscv64-linux-g  155191 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.912  cc1              155195 155191   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.917  riscv64-linux-g  155194 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.921  riscv64-linux-g  155196 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.925  cc1              155198 155194   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.925  cc1              155199 155196   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.931  riscv64-linux-g  155197 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.935  riscv64-linux-g  155200 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.940  cc1              155202 155197   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.942  cc1              155201 155200   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -lang-asm -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= ...\n12.956  as               155203 155128   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/88f362f13b0528ed-huf_decompress.o /tmp/ccX1jBFh.s\n12.960  as               155204 155200   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/7faed3f8272f2313-huf_decompress_amd64.o /tmp/ccB5Eklk.s\n12.971  as               155205 155121   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_opt.o /tmp/ccnyQG7n.s\n12.992  as               155206 155174   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v02.o /tmp/ccz7pu4m.s\n12.994  abrt-handle-eve  155207 155030   0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n13.015  sh               155208 155207   0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n13.018  dbus-send        155208 155207   0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n13.024  sh               155209 155207   0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n13.025  abrt-action-not  155210 155209   0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n13.056  as               155211 155157   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/88f362f13b0528ed-zstd_decompress_block.o /tmp/ccK9lDte.s\n13.082  as               155212 155189   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v03.o /tmp/ccFVhhZC.s\n13.092  as               155213 155101   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_compress.o /tmp/ccdOd9ky.s\n13.094  as               155214 155196   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v06.o /tmp/ccj3biUE.s\n13.103  sh               155215 155210   0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n13.105  as               155216 155191   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v04.o /tmp/ccBnxzcp.s\n13.105  reporter-system  155215 155210   0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n13.131  as               155219 155194   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v05.o /tmp/ccWKrAA3.s\n13.154  as               155220 155197   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v07.o /tmp/ccI4pcXm.s\n13.456  as               155221 154928   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_lazy.o /tmp/cc3dev06.s\n13.888  as               155222 155116   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_lazy.o /tmp/ccx9UrSH.s\n13.931  powerpc64le-lin  155223 154796   0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/libzstd.a /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-debug.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-entropy_common.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-error_private.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-fse_decompress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-pool.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-threading.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-zstd_common.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-fse_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-hist.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-huf_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_compress_literals.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_compress_sequences.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_compress_superblock.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_double_fast.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_fast.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_lazy.o ...\n13.932  cross            155224 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n13.932  cross            155225 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n13.933  rustc            155227 155224   0 /home/xmoe/.cargo/bin/rustc --print target-list\n13.933  rustc            155228 155225   0 /home/xmoe/.cargo/bin/rustc --print target-list\n13.938  rustc            155227 155224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n13.940  rustc            155228 155225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n13.947  cross            155250 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n13.949  rustc            155257 155250   0 /home/xmoe/.cargo/bin/rustc --print target-list\n13.949  powerpc64le-lin  155258 154796   0 \n13.951  rustc            155259 155225   0 /home/xmoe/.cargo/bin/rustc -vV\n13.952  rustc            155260 155224   0 /home/xmoe/.cargo/bin/rustc -vV\n13.955  rustc            155257 155250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n13.957  rustc            155260 155224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.958  rustc            155259 155225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.965  cargo            155291 155224   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n13.966  llvm-config      155290 154796   0 /usr/bin/llvm-config --prefix\n13.967  cargo            155292 155225   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n13.969  rustc            155301 155250   0 /home/xmoe/.cargo/bin/rustc -vV\n13.971  cargo            155291 155224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n13.973  cargo            155292 155225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n13.975  rustc            155301 155250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.982  rustc            155318 155291   0 \n13.984  rustc            155320 155292   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.986  cargo            155321 155250   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n13.991  cargo            155321 155250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n13.992  rustc            155332 155291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.994  rustc            155333 155292   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.003  rustc            155340 155321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.005  rustc            155341 155292   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.005  rustc            155342 155291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.014  rustc            155350 155321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.026  rustc            155355 155321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.115  llvm-config      155359 154796   0 /usr/bin/llvm-config --bindir\n14.124  clang            155360 154796   0 /usr/lib/llvm-10/bin/clang --version\n14.248  clang            155362 154796   0 /usr/lib/llvm-10/bin/clang -E -x c - -v --target=powerpc64le-unknown-linux-gnu --sysroot=/usr/powerpc64le-linux-gnu -idirafter/usr/include -include zstd.h\n14.254  riscv64-linux-g  155363 155026   0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/libzstd.a /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-debug.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-entropy_common.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-error_private.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-fse_decompress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-pool.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-threading.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-zstd_common.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-fse_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-hist.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-huf_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_compress_literals.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_compress_sequences.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_compress_superblock.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_double_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_lazy.o ...\n14.286  clang            155364 154796   0 /usr/lib/llvm-10/bin/clang -E -x c++ - -v --target=powerpc64le-unknown-linux-gnu --sysroot=/usr/powerpc64le-linux-gnu -idirafter/usr/include -include zstd.h\n14.315  riscv64-linux-g  155367 155026   0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/libzstd.a\n14.382  llvm-config      155368 155026   0 /usr/bin/llvm-config --prefix\n14.412  rustfmt          155369 154796   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustfmt\n14.414  sh               155371 2147557   0 /bin/sh -c which ps\n14.416  which            155371 2147557   0 /usr/bin/which ps\n14.418  sh               155372 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.419  ps               155372 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.435  rustc            155374 151215   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"bindgen\" --cfg feature=\"default\" --cfg ...\n14.443  sh               155375 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n14.444  cpuUsage.sh      155375 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n14.446  sed              155379 155375   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.448  cat              155380 155375   0 /usr/bin/cat /proc/2240539/stat\n14.449  cat              155381 155375   0 /usr/bin/cat /proc/4193716/stat\n14.450  sleep            155382 155375   0 /usr/bin/sleep 1\n14.528  llvm-config      155386 155026   0 /usr/bin/llvm-config --bindir\n14.531  clang            155387 155026   0 /usr/lib/llvm-14/bin/clang --version\n14.624  clang            155388 155026   0 /usr/lib/llvm-14/bin/clang -E -x c - -v --target=riscv64-unknown-linux-gnu --sysroot=/usr/riscv64-linux-gnu -idirafter/usr/include -include zstd.h\n14.661  clang            155389 155026   0 /usr/lib/llvm-14/bin/clang -E -x c++ - -v --target=riscv64-unknown-linux-gnu --sysroot=/usr/riscv64-linux-gnu -idirafter/usr/include -include zstd.h\n14.783  rustfmt          155391 155026   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustfmt\n14.805  rustc            155394 152412   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"bindgen\" --cfg feature=\"default\" --cfg ...\n15.352  rustc            155401 155291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.379  rustc            155403 155292   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.406  rustc            155405 155321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.431  rustc            155407 155224   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.432  rustc            155408 155225   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.437  rustc            155408 155225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.437  rustc            155407 155224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.448  rustc            155431 155250   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.448  docker           155432 155225   0 /usr/bin/docker --help\n15.449  docker           155433 155224   0 /usr/bin/docker --help\n15.451  sed              155452 155375   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.453  rustc            155431 155250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.454  cat              155453 155375   0 /usr/bin/cat /proc/2240539/stat\n15.456  cat              155456 155375   0 /usr/bin/cat /proc/4193716/stat\n15.462  docker           155473 155225   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.463  docker           155474 155224   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.466  docker           155485 155250   0 /usr/bin/docker --help\n15.473  runc             155501 1599     0 /usr/bin/runc --version\n15.474  runc             155506 1599     0 /usr/bin/runc --version\n15.476  docker-init      155517 1599     0 /usr/bin/docker-init --version\n15.477  docker-init      155518 1599     0 /usr/bin/docker-init --version\n15.478  docker           155519 155225   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.479  docker           155520 155224   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.481  docker           155531 155250   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.490  runc             155549 1599     0 /usr/bin/runc --version\n15.492  runc             155554 1599     0 /usr/bin/runc --version\n15.493  runc             155559 1599     0 /usr/bin/runc --version\n15.494  docker-init      155564 1599     0 /usr/bin/docker-init --version\n15.496  docker-init      155571 1599     0 /usr/bin/docker-init --version\n15.496  docker-init      155572 1599     0 /usr/bin/docker-init --version\n15.498  docker           155573 155250   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.510  runc             155588 1599     0 /usr/bin/runc --version\n15.513  docker-init      155594 1599     0 /usr/bin/docker-init --version\n15.516  rustup           155595 155225   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.520  rustup           155604 155224   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.522  rustup           155605 155225   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.526  rustup           155622 155224   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.536  rustup           155631 155250   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.542  rustup           155640 155250   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.546  rustup           155649 155225   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.550  rustup           155658 155224   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.568  rustup           155667 155250   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.570  uname            155668 155225   0 /usr/bin/uname -r\n15.573  uname            155677 155224   0 /usr/bin/uname -r\n15.587  docker           155678 155225   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.591  docker           155684 155224   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.594  uname            155685 155250   0 /usr/bin/uname -r\n15.613  docker           155700 155250   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.632  systemd-sysctl   155724 155722   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7e9cf7b --prefix=/net/ipv4/neigh/veth7e9cf7b --prefix=/net/ipv6/conf/veth7e9cf7b --prefix=/net/ipv6/neigh/veth7e9cf7b\n15.633  systemd-sysctl   155725 155723   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha489837 --prefix=/net/ipv4/neigh/vetha489837 --prefix=/net/ipv6/conf/vetha489837 --prefix=/net/ipv6/neigh/vetha489837\n15.636  systemd-sysctl   155728 155726   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda9a202 --prefix=/net/ipv4/neigh/vethda9a202 --prefix=/net/ipv6/conf/vethda9a202 --prefix=/net/ipv6/neigh/vethda9a202\n15.637  systemd-sysctl   155729 155727   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5716b6b --prefix=/net/ipv4/neigh/veth5716b6b --prefix=/net/ipv6/conf/veth5716b6b --prefix=/net/ipv6/neigh/veth5716b6b\n15.691  systemd-sysctl   155761 155732   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4f94b4 --prefix=/net/ipv4/neigh/vethf4f94b4 --prefix=/net/ipv6/conf/vethf4f94b4 --prefix=/net/ipv6/neigh/vethf4f94b4\n15.691  systemd-sysctl   155762 155739   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8c45214 --prefix=/net/ipv4/neigh/veth8c45214 --prefix=/net/ipv6/conf/veth8c45214 --prefix=/net/ipv6/neigh/veth8c45214\n15.750  containerd-shim  155763 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 start\n15.753  containerd-shim  155769 155763   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 -address /var/run/docker/containerd/containerd.sock\n15.757  runc             155779 155769   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731\n15.762  exe              155788 155779   0 /proc/self/exe init\n15.801  exe              155796 155779   0 /proc/1599/exe -exec-root=/var/run/docker e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 d7da31e8f8e1\n15.819  exe              155804 1599     0 /proc/self/exe /var/run/docker/netns/3a348ec5d0f1 all false\n15.853  containerd-shim  155820 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb start\n15.855  containerd-shim  155824 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea start\n15.856  containerd-shim  155832 155820   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb -address /var/run/docker/containerd/containerd.sock\n15.857  containerd-shim  155839 155824   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea -address /var/run/docker/containerd/containerd.sock\n15.860  runc             155855 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb\n15.861  runc             155856 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea\n15.866  exe              155871 155855   0 /proc/self/exe init\n15.867  exe              155872 155856   0 /proc/self/exe init\n15.868  runc             155875 155769   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --log-format json --systemd-cgroup start e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731\n15.874  sh               155790 155769   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.875  cargo            155882 155790   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.886  cargo-native-tr  155882 155790   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.889  cargo            155897 155882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.894  exe              155898 155856   0 /proc/1599/exe -exec-root=/var/run/docker 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea d7da31e8f8e1\n15.895  exe              155899 155855   0 /proc/1599/exe -exec-root=/var/run/docker d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb d7da31e8f8e1\n15.901  rustc            155910 155897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV /bin/rustc -vV\n15.913  exe              155916 1599     0 /proc/self/exe /var/run/docker/netns/20e6cea9bf06 all false\n15.913  rustc            155915 155897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.915  exe              155917 1599     0 /proc/self/exe /var/run/docker/netns/4ce422236531 all false\n15.936  execsnoop        155950 155882   0 /usr/local/bin/execsnoop -t\n15.937  python3          155950 155882   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.981  runc             155954 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup start d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb\n15.982  runc             155955 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup start 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea\n15.987  sh               155891 155832   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.988  sh               155884 155839   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.988  cargo            155965 155891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n15.989  cargo            155966 155884   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n15.999  cargo-native-tr  155966 155884   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n16.001  cargo-native-tr  155965 155891   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.003  cargo            155967 155966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.005  cargo            155968 155965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.014  rustc            155969 155967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.015  rustc            155970 155968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.025  rustc            155973 155967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.027  rustc            155974 155968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.052  execsnoop        155981 155965   0 /usr/local/bin/execsnoop -t\n16.053  python3          155981 155965   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.053  execsnoop        155984 155966   0 /usr/local/bin/execsnoop -t\n16.054  python3          155984 155966   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.242  16               155987 1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n16.256  frpc             155987 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.957  cargo            155993 155965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.960  cargo            155994 155966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n17.972  rustc            155995 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.973  rustc            155996 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.998  rustc            156009 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"defmt-03\", \"mpmc_large\", \"portable-atomic\", \"portable-atomic-critical-section\", \"portable-atomic-unsafe-ass -C metadata=0bcf272fd4a41228 ...\n17.998  rustc            156010 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n17.998  rustc            156011 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name byteorder --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"i128\", \"std\")) -C metadata=c48b90dfbbda9f5e ...\n18.001  rustc            156012 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name stable_deref_trait --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stable_deref_trait-1.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"default\", \"std\")) -C metadata=142658315e27326b ...\n18.079  rustc            156052 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hash32 --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hash32-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=871b075c5f9c75b5 ...\n18.105  cc               156086 156009   0 /tmp/native-trace-155966-1783993104406/shims/cc -m64 /target/debug/build/heapless-1640e7d816e37021/rustcB5MYOH/symbols.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.003xu6mngsx05pt7soakh8kmx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.01vzefae9ykg3tha98hqn4qjd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.03q26do3xj4reflzp4ujkhtou.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0rqdwaxd1mao1yhu1t1qhncts.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0xa7kgbuw0i07l44ujmiazs1v.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.1ic2mqya3v3laouyh8018e7yu.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.21d9n7nvjp9whhlnjfwrzcaip.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2chmhzmce29un2p5aqvsy15jh.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2h4lopnp3woikeonplzmhc0nv.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2mju1ukg99b0yv1s0g0opq28d.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2n6t2sx4jts63nobe1ju4xofx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rhokkseltpqc9andmx6u2r2w.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rw4yme7h7aehc6u1ma26fxum.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2zvb2xpkrh4onudn3rzvmu7k4.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3k1vkeh97ivuanpaqm9wnbm35.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mohzrrezerp65vdqoaar8xtd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mon2525yms8rau8qxu3n5jd4.1uwodqe.rcgu.o ...\n18.106  cc               156087 156086   0 /usr/bin/cc -m64 /target/debug/build/heapless-1640e7d816e37021/rustcB5MYOH/symbols.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.003xu6mngsx05pt7soakh8kmx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.01vzefae9ykg3tha98hqn4qjd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.03q26do3xj4reflzp4ujkhtou.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0rqdwaxd1mao1yhu1t1qhncts.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0xa7kgbuw0i07l44ujmiazs1v.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.1ic2mqya3v3laouyh8018e7yu.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.21d9n7nvjp9whhlnjfwrzcaip.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2chmhzmce29un2p5aqvsy15jh.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2h4lopnp3woikeonplzmhc0nv.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2mju1ukg99b0yv1s0g0opq28d.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2n6t2sx4jts63nobe1ju4xofx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rhokkseltpqc9andmx6u2r2w.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rw4yme7h7aehc6u1ma26fxum.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2zvb2xpkrh4onudn3rzvmu7k4.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3k1vkeh97ivuanpaqm9wnbm35.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mohzrrezerp65vdqoaar8xtd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mon2525yms8rau8qxu3n5jd4.1uwodqe.rcgu.o ...\n18.111  collect2         156088 156087   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.113  ld.lld           156091 156088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021 ...\n18.114  rust-lld         156091 156088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.125  runc             156095 146687   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 --log-format json --systemd-cgroup kill --all 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c 9\n18.145  runc             156120 146687   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 --log-format json --systemd-cgroup delete 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c\n18.175  build-script-bu  156129 155994   0 /target/debug/build/heapless-1640e7d816e37021/build-script-build\n18.180  rustc            156131 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name heapless --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"defmt-03\", \"mpmc_large\", \"portable-atomic\", \"portable-atomic-critical-section\", \"portable-atomic-unsafe-ass -C metadata=81506217a3a7e12c ...\n18.197  cargo            156136 155882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.211  rustc            156137 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.222  rustc            156142 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=8eab25d199e7deb9 ...\n18.232  rustc            156145 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n18.253  cc               156159 156142   0 /tmp/native-trace-155965-1783993104408/shims/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcsi6iI5/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.0co4w98.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n18.254  cc               156160 156159   0 /usr/bin/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcsi6iI5/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.0co4w98.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n18.257  collect2         156161 156160   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.258  ld.lld           156162 156161   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b ...\n18.260  rust-lld         156162 156161   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.302  build-script-bu  156180 155993   0 /target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build\n18.304  rustc            156181 156180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n18.315  rustc            156183 156180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_ae266a08b08eb5bb_0 --crate-type=lib --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/fs-err-6e7f7f43f71799c8/out --emit=llvm-ir --target powerpc64le-unknown-linux-gnu -\n18.337  containerd-shim  156194 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 delete\n18.337  rustc            156193 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_err --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=ea980410505747aa ...\n18.340  runc             156201 156194   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434 --log-format json delete --force 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c\n18.374  systemd-sysctl   156212 155732   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth649a077 --prefix=/net/ipv4/neigh/veth649a077 --prefix=/net/ipv6/conf/veth649a077 --prefix=/net/ipv6/neigh/veth649a077\n18.435  rustc            156216 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=8eab25d199e7deb9 ...\n18.466  cc               156242 156216   0 /tmp/native-trace-155882-1783993104292/shims/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n18.468  cc               156249 156242   0 /usr/bin/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n18.470  collect2         156253 156249   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.472  ld.lld           156256 156253   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b ...\n18.474  rust-lld         156256 156253   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.514  build-script-bu  156298 156136   0 /target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build\n18.516  rustc            156299 156298   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n18.528  rustc            156301 156298   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_77a383603c224a07_0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/fs-err-d223f2b3d73c7254/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n18.548  rustc            156309 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_err --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=e5fa82910511c4ea ...\n"
}
```

#### Record 18

```json
{
  "argv": [
    "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 151837,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build",
  "pid": 151837,
  "ppid": 151102,
  "root_cargo_pid": 151102,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
  "build_script_root_pid": 151837,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 151840,
  "ppid": 151837,
  "root_cargo_pid": 151102,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "_build_script_out_dir": "/target/debug/build/slotmap-9cd0fd3344a99352/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
  "build_script_root_pid": 151837,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 151847,
  "ppid": 151837,
  "root_cargo_pid": 151102,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "_build_script_out_dir": "/target/debug/build/slotmap-9cd0fd3344a99352/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
  "build_script_root_pid": 151837,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 151873,
  "ppid": 151837,
  "root_cargo_pid": 151102,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "_build_script_out_dir": "/target/debug/build/slotmap-9cd0fd3344a99352/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 22

```json
{
  "crate": "slotmap",
  "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "event_id": "bsrun:d20aa50d73e1f0e5:31fc1c25b134e6d5:0b48ffbf0383fa98",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
  "out_dir": "/target/debug/build/slotmap-9cd0fd3344a99352/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
  "success": true,
  "target": null,
  "version": "1.0.7",
  "_owner": {
    "crate": "slotmap",
    "version": "1.0.7",
    "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
    "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
  "build_script_root_pid": 151837,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 151840,
  "ppid": 151837,
  "root_cargo_pid": 151102,
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
  "build_script_root_pid": 151837,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 151847,
  "ppid": 151837,
  "root_cargo_pid": 151102,
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
  "build_script_root_pid": 151837,
  "build_script_target_dir": "slotmap-9cd0fd3344a99352",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 151873,
  "ppid": 151837,
  "root_cargo_pid": 151102,
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
  "time": "2026-07-14T01:38:27.532698+00:00",
  "crate": "slotmap",
  "version": "1.0.7",
  "architecture": "aarch64",
  "duration_seconds": 23.424488838762045,
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
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "manifest_path": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7/Cargo.toml"
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "workspace_root": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7"
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
          "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
          "name": "slotmap",
          "version": "1.0.7",
          "manifest_path": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7"
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
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "exit_code": 0,
      "kind": "exec",
      "pid": 151652,
      "ppid": 151530,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "event_id": "used:cc:f3e8477555a12adb:b4bcb6bde2261afe:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
      "pid": 151652,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "event_id": "used:cc:f3e8477555a12adb:5b81127e15da9f65:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
      "pid": 151652,
      "sha256": "f3e81bc2c03c5b802d3096189bd58f403463e454317386e32339cd9fcd9045d3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "event_id": "used:cc:f3e8477555a12adb:499e2b28141362a4:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
      "pid": 151652,
      "sha256": "8df2dd9e7878fa6958bacbd264ac90161bb0df333483e42b0bcce9eaa9ac626b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "event_id": "used:cc:f3e8477555a12adb:09e6047fb722a6fa:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
      "pid": 151652,
      "sha256": "1078c6244058e5e602b0969a0cc6a5b467b876533e2c9abc119b5f276a904401",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "event_id": "used:cc:f3e8477555a12adb:c3dc114ab019ca47:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
      "pid": 151652,
      "sha256": "0e130ddcc57638083634963a4fb65b253da1ec94bec0173c096b438ce5f755e3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "event_id": "used:cc:f3e8477555a12adb:b60ab212de479482:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
      "pid": 151652,
      "sha256": "76aa16517bef0f41c80fd4ce0ef1e58dad71dbfbb9d9ff35ede1e5c3d99b5cb9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "event_id": "used:cc:f3e8477555a12adb:162c7cd83597ff0f:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
      "pid": 151652,
      "sha256": "01575e290b2f767ccd2644f1f63e4810fd6a090e22999ad9a56b4a4164e85a34",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "event_id": "used:cc:f3e8477555a12adb:f836a0976d3a5870:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
      "pid": 151652,
      "sha256": "c7f6a519914a011d3bfc1a3078b3b5df0bb010775b0d2b2643cde70754b7fa2b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "event_id": "used:cc:f3e8477555a12adb:31e755c529a01f99:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
      "pid": 151652,
      "sha256": "fa997913a33ac1f8ad61e125c33a5ab771b9d6c494bf733b54de187600cf2e42",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "event_id": "used:cc:f3e8477555a12adb:f1fda6e891156753:3eb20d85f4f09b6f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352",
      "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
      "pid": 151652,
      "sha256": "19e4a3cc62f0b57413eb48adfdf7b9c6c64181801a9976c8a83f99accc17b5c4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "cargo_pkg_name": "slotmap",
      "cargo_pkg_version": "1.0.7",
      "context_path": "/tmp/native-trace-150515-1783993085902/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-150515-1783993085902/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 151652,
      "ppid": 151530,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
        "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx",
        "/target/debug/build/slotmap-9cd0fd3344a99352",
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
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/rustcTn82Lx/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.06joqh5r73pmf8zcfr6e42h3z.025zg2c.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.12ghht6ync58mmrijpisseqax.025zg2c.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1jzqwx21q0zjbpoqd23ts73i7.025zg2c.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.1q4iv0nid43v0ep69k9g7u0as.025zg2c.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.79xybc32m4px83jqng0wptc5m.025zg2c.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.8kmk9o6cvcvjiehztsfdz9d58.025zg2c.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.e5zey6fdg7mka3vtcrhnzk6a5.025zg2c.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.ecvhy09lm6cee82zroso0rze3.025zg2c.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slotmap-9cd0fd3344a99352",
          "kind": "object",
          "path": "/target/debug/build/slotmap-9cd0fd3344a99352/build_script_build-9cd0fd3344a99352.7jxnq0iod13li44z5y12c8a29.025zg2c.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-151652-1783993088991942016.map",
      "pid": 151652,
      "ppid": 151530,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-151652-1783993088991942016.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
      "parsed_event_count": 1188,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1189,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "r/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/88f362f13b0528ed-zstd_decompress.o /tmp/ccRqsFaT.s\n12.900  as               155190 155113   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_fast.o /tmp/ccEd3pLN.s\n12.902  riscv64-linux-g  155189 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.906  abrt-action-cor  155192 155074   0 /usr/libexec/abrt-action-coredump -r\n12.908  cc1              155193 155189   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.910  riscv64-linux-g  155191 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.912  cc1              155195 155191   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.917  riscv64-linux-g  155194 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.921  riscv64-linux-g  155196 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.925  cc1              155198 155194   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.925  cc1              155199 155196   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.931  riscv64-linux-g  155197 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.935  riscv64-linux-g  155200 155026   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.940  cc1              155202 155197   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.942  cc1              155201 155200   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -lang-asm -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= ...\n12.956  as               155203 155128   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/88f362f13b0528ed-huf_decompress.o /tmp/ccX1jBFh.s\n12.960  as               155204 155200   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/7faed3f8272f2313-huf_decompress_amd64.o /tmp/ccB5Eklk.s\n12.971  as               155205 155121   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_opt.o /tmp/ccnyQG7n.s\n12.992  as               155206 155174   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v02.o /tmp/ccz7pu4m.s\n12.994  abrt-handle-eve  155207 155030   0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n13.015  sh               155208 155207   0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n13.018  dbus-send        155208 155207   0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n13.024  sh               155209 155207   0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n13.025  abrt-action-not  155210 155209   0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n13.056  as               155211 155157   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/88f362f13b0528ed-zstd_decompress_block.o /tmp/ccK9lDte.s\n13.082  as               155212 155189   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v03.o /tmp/ccFVhhZC.s\n13.092  as               155213 155101   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_compress.o /tmp/ccdOd9ky.s\n13.094  as               155214 155196   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v06.o /tmp/ccj3biUE.s\n13.103  sh               155215 155210   0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n13.105  as               155216 155191   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v04.o /tmp/ccBnxzcp.s\n13.105  reporter-system  155215 155210   0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n13.131  as               155219 155194   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v05.o /tmp/ccWKrAA3.s\n13.154  as               155220 155197   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/3f451b2306bc13c8-zstd_v07.o /tmp/ccI4pcXm.s\n13.456  as               155221 154928   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_lazy.o /tmp/cc3dev06.s\n13.888  as               155222 155116   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_lazy.o /tmp/ccx9UrSH.s\n13.931  powerpc64le-lin  155223 154796   0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/libzstd.a /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-debug.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-entropy_common.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-error_private.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-fse_decompress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-pool.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-threading.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/44ff4c55aa9e5133-zstd_common.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-fse_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-hist.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-huf_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_compress_literals.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_compress_sequences.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_compress_superblock.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_double_fast.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_fast.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-96fd668a4bcfea82/out/fb80479a5fb81f6a-zstd_lazy.o ...\n13.932  cross            155224 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n13.932  cross            155225 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n13.933  rustc            155227 155224   0 /home/xmoe/.cargo/bin/rustc --print target-list\n13.933  rustc            155228 155225   0 /home/xmoe/.cargo/bin/rustc --print target-list\n13.938  rustc            155227 155224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n13.940  rustc            155228 155225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n13.947  cross            155250 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n13.949  rustc            155257 155250   0 /home/xmoe/.cargo/bin/rustc --print target-list\n13.949  powerpc64le-lin  155258 154796   0 \n13.951  rustc            155259 155225   0 /home/xmoe/.cargo/bin/rustc -vV\n13.952  rustc            155260 155224   0 /home/xmoe/.cargo/bin/rustc -vV\n13.955  rustc            155257 155250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n13.957  rustc            155260 155224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.958  rustc            155259 155225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.965  cargo            155291 155224   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n13.966  llvm-config      155290 154796   0 /usr/bin/llvm-config --prefix\n13.967  cargo            155292 155225   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n13.969  rustc            155301 155250   0 /home/xmoe/.cargo/bin/rustc -vV\n13.971  cargo            155291 155224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n13.973  cargo            155292 155225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n13.975  rustc            155301 155250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.982  rustc            155318 155291   0 \n13.984  rustc            155320 155292   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.986  cargo            155321 155250   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n13.991  cargo            155321 155250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n13.992  rustc            155332 155291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.994  rustc            155333 155292   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.003  rustc            155340 155321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.005  rustc            155341 155292   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.005  rustc            155342 155291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.014  rustc            155350 155321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.026  rustc            155355 155321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.115  llvm-config      155359 154796   0 /usr/bin/llvm-config --bindir\n14.124  clang            155360 154796   0 /usr/lib/llvm-10/bin/clang --version\n14.248  clang            155362 154796   0 /usr/lib/llvm-10/bin/clang -E -x c - -v --target=powerpc64le-unknown-linux-gnu --sysroot=/usr/powerpc64le-linux-gnu -idirafter/usr/include -include zstd.h\n14.254  riscv64-linux-g  155363 155026   0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/libzstd.a /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-debug.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-entropy_common.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-error_private.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-fse_decompress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-pool.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-threading.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/44ff4c55aa9e5133-zstd_common.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-fse_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-hist.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-huf_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_compress_literals.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_compress_sequences.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_compress_superblock.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_double_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/fb80479a5fb81f6a-zstd_lazy.o ...\n14.286  clang            155364 154796   0 /usr/lib/llvm-10/bin/clang -E -x c++ - -v --target=powerpc64le-unknown-linux-gnu --sysroot=/usr/powerpc64le-linux-gnu -idirafter/usr/include -include zstd.h\n14.315  riscv64-linux-g  155367 155026   0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-362b43de3e4cddd5/out/libzstd.a\n14.382  llvm-config      155368 155026   0 /usr/bin/llvm-config --prefix\n14.412  rustfmt          155369 154796   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustfmt\n14.414  sh               155371 2147557   0 /bin/sh -c which ps\n14.416  which            155371 2147557   0 /usr/bin/which ps\n14.418  sh               155372 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.419  ps               155372 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.435  rustc            155374 151215   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"bindgen\" --cfg feature=\"default\" --cfg ...\n14.443  sh               155375 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n14.444  cpuUsage.sh      155375 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n14.446  sed              155379 155375   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.448  cat              155380 155375   0 /usr/bin/cat /proc/2240539/stat\n14.449  cat              155381 155375   0 /usr/bin/cat /proc/4193716/stat\n14.450  sleep            155382 155375   0 /usr/bin/sleep 1\n14.528  llvm-config      155386 155026   0 /usr/bin/llvm-config --bindir\n14.531  clang            155387 155026   0 /usr/lib/llvm-14/bin/clang --version\n14.624  clang            155388 155026   0 /usr/lib/llvm-14/bin/clang -E -x c - -v --target=riscv64-unknown-linux-gnu --sysroot=/usr/riscv64-linux-gnu -idirafter/usr/include -include zstd.h\n14.661  clang            155389 155026   0 /usr/lib/llvm-14/bin/clang -E -x c++ - -v --target=riscv64-unknown-linux-gnu --sysroot=/usr/riscv64-linux-gnu -idirafter/usr/include -include zstd.h\n14.783  rustfmt          155391 155026   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustfmt\n14.805  rustc            155394 152412   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"bindgen\" --cfg feature=\"default\" --cfg ...\n15.352  rustc            155401 155291   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.379  rustc            155403 155292   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.406  rustc            155405 155321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.431  rustc            155407 155224   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.432  rustc            155408 155225   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.437  rustc            155408 155225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.437  rustc            155407 155224   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.448  rustc            155431 155250   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.448  docker           155432 155225   0 /usr/bin/docker --help\n15.449  docker           155433 155224   0 /usr/bin/docker --help\n15.451  sed              155452 155375   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.453  rustc            155431 155250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.454  cat              155453 155375   0 /usr/bin/cat /proc/2240539/stat\n15.456  cat              155456 155375   0 /usr/bin/cat /proc/4193716/stat\n15.462  docker           155473 155225   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.463  docker           155474 155224   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.466  docker           155485 155250   0 /usr/bin/docker --help\n15.473  runc             155501 1599     0 /usr/bin/runc --version\n15.474  runc             155506 1599     0 /usr/bin/runc --version\n15.476  docker-init      155517 1599     0 /usr/bin/docker-init --version\n15.477  docker-init      155518 1599     0 /usr/bin/docker-init --version\n15.478  docker           155519 155225   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.479  docker           155520 155224   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.481  docker           155531 155250   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.490  runc             155549 1599     0 /usr/bin/runc --version\n15.492  runc             155554 1599     0 /usr/bin/runc --version\n15.493  runc             155559 1599     0 /usr/bin/runc --version\n15.494  docker-init      155564 1599     0 /usr/bin/docker-init --version\n15.496  docker-init      155571 1599     0 /usr/bin/docker-init --version\n15.496  docker-init      155572 1599     0 /usr/bin/docker-init --version\n15.498  docker           155573 155250   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.510  runc             155588 1599     0 /usr/bin/runc --version\n15.513  docker-init      155594 1599     0 /usr/bin/docker-init --version\n15.516  rustup           155595 155225   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.520  rustup           155604 155224   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.522  rustup           155605 155225   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.526  rustup           155622 155224   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.536  rustup           155631 155250   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.542  rustup           155640 155250   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.546  rustup           155649 155225   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.550  rustup           155658 155224   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.568  rustup           155667 155250   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.570  uname            155668 155225   0 /usr/bin/uname -r\n15.573  uname            155677 155224   0 /usr/bin/uname -r\n15.587  docker           155678 155225   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.591  docker           155684 155224   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.594  uname            155685 155250   0 /usr/bin/uname -r\n15.613  docker           155700 155250   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.632  systemd-sysctl   155724 155722   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7e9cf7b --prefix=/net/ipv4/neigh/veth7e9cf7b --prefix=/net/ipv6/conf/veth7e9cf7b --prefix=/net/ipv6/neigh/veth7e9cf7b\n15.633  systemd-sysctl   155725 155723   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha489837 --prefix=/net/ipv4/neigh/vetha489837 --prefix=/net/ipv6/conf/vetha489837 --prefix=/net/ipv6/neigh/vetha489837\n15.636  systemd-sysctl   155728 155726   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda9a202 --prefix=/net/ipv4/neigh/vethda9a202 --prefix=/net/ipv6/conf/vethda9a202 --prefix=/net/ipv6/neigh/vethda9a202\n15.637  systemd-sysctl   155729 155727   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5716b6b --prefix=/net/ipv4/neigh/veth5716b6b --prefix=/net/ipv6/conf/veth5716b6b --prefix=/net/ipv6/neigh/veth5716b6b\n15.691  systemd-sysctl   155761 155732   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4f94b4 --prefix=/net/ipv4/neigh/vethf4f94b4 --prefix=/net/ipv6/conf/vethf4f94b4 --prefix=/net/ipv6/neigh/vethf4f94b4\n15.691  systemd-sysctl   155762 155739   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8c45214 --prefix=/net/ipv4/neigh/veth8c45214 --prefix=/net/ipv6/conf/veth8c45214 --prefix=/net/ipv6/neigh/veth8c45214\n15.750  containerd-shim  155763 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 start\n15.753  containerd-shim  155769 155763   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 -address /var/run/docker/containerd/containerd.sock\n15.757  runc             155779 155769   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731\n15.762  exe              155788 155779   0 /proc/self/exe init\n15.801  exe              155796 155779   0 /proc/1599/exe -exec-root=/var/run/docker e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731 d7da31e8f8e1\n15.819  exe              155804 1599     0 /proc/self/exe /var/run/docker/netns/3a348ec5d0f1 all false\n15.853  containerd-shim  155820 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb start\n15.855  containerd-shim  155824 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea start\n15.856  containerd-shim  155832 155820   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb -address /var/run/docker/containerd/containerd.sock\n15.857  containerd-shim  155839 155824   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea -address /var/run/docker/containerd/containerd.sock\n15.860  runc             155855 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb\n15.861  runc             155856 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea\n15.866  exe              155871 155855   0 /proc/self/exe init\n15.867  exe              155872 155856   0 /proc/self/exe init\n15.868  runc             155875 155769   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053c --log-format json --systemd-cgroup start e40414e49f7806c71c2a4c3e04da24a7a738505fc28d68a72cca683053cdb731\n15.874  sh               155790 155769   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.875  cargo            155882 155790   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.886  cargo-native-tr  155882 155790   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.889  cargo            155897 155882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.894  exe              155898 155856   0 /proc/1599/exe -exec-root=/var/run/docker 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea d7da31e8f8e1\n15.895  exe              155899 155855   0 /proc/1599/exe -exec-root=/var/run/docker d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb d7da31e8f8e1\n15.901  rustc            155910 155897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV /bin/rustc -vV\n15.913  exe              155916 1599     0 /proc/self/exe /var/run/docker/netns/20e6cea9bf06 all false\n15.913  rustc            155915 155897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.915  exe              155917 1599     0 /proc/self/exe /var/run/docker/netns/4ce422236531 all false\n15.936  execsnoop        155950 155882   0 /usr/local/bin/execsnoop -t\n15.937  python3          155950 155882   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.981  runc             155954 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup start d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb\n15.982  runc             155955 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup start 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea\n15.987  sh               155891 155832   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.988  sh               155884 155839   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.988  cargo            155965 155891   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n15.989  cargo            155966 155884   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n15.999  cargo-native-tr  155966 155884   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n16.001  cargo-native-tr  155965 155891   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.003  cargo            155967 155966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.005  cargo            155968 155965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.014  rustc            155969 155967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.015  rustc            155970 155968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.025  rustc            155973 155967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.027  rustc            155974 155968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.052  execsnoop        155981 155965   0 /usr/local/bin/execsnoop -t\n16.053  python3          155981 155965   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.053  execsnoop        155984 155966   0 /usr/local/bin/execsnoop -t\n16.054  python3          155984 155966   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.242  16               155987 1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n16.256  frpc             155987 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.957  cargo            155993 155965   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.960  cargo            155994 155966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n17.972  rustc            155995 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.973  rustc            155996 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.998  rustc            156009 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"defmt-03\", \"mpmc_large\", \"portable-atomic\", \"portable-atomic-critical-section\", \"portable-atomic-unsafe-ass -C metadata=0bcf272fd4a41228 ...\n17.998  rustc            156010 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n17.998  rustc            156011 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name byteorder --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"i128\", \"std\")) -C metadata=c48b90dfbbda9f5e ...\n18.001  rustc            156012 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name stable_deref_trait --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stable_deref_trait-1.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"default\", \"std\")) -C metadata=142658315e27326b ...\n18.079  rustc            156052 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hash32 --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hash32-0.3.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=871b075c5f9c75b5 ...\n18.105  cc               156086 156009   0 /tmp/native-trace-155966-1783993104406/shims/cc -m64 /target/debug/build/heapless-1640e7d816e37021/rustcB5MYOH/symbols.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.003xu6mngsx05pt7soakh8kmx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.01vzefae9ykg3tha98hqn4qjd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.03q26do3xj4reflzp4ujkhtou.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0rqdwaxd1mao1yhu1t1qhncts.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0xa7kgbuw0i07l44ujmiazs1v.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.1ic2mqya3v3laouyh8018e7yu.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.21d9n7nvjp9whhlnjfwrzcaip.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2chmhzmce29un2p5aqvsy15jh.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2h4lopnp3woikeonplzmhc0nv.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2mju1ukg99b0yv1s0g0opq28d.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2n6t2sx4jts63nobe1ju4xofx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rhokkseltpqc9andmx6u2r2w.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rw4yme7h7aehc6u1ma26fxum.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2zvb2xpkrh4onudn3rzvmu7k4.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3k1vkeh97ivuanpaqm9wnbm35.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mohzrrezerp65vdqoaar8xtd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mon2525yms8rau8qxu3n5jd4.1uwodqe.rcgu.o ...\n18.106  cc               156087 156086   0 /usr/bin/cc -m64 /target/debug/build/heapless-1640e7d816e37021/rustcB5MYOH/symbols.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.003xu6mngsx05pt7soakh8kmx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.01vzefae9ykg3tha98hqn4qjd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.03q26do3xj4reflzp4ujkhtou.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0rqdwaxd1mao1yhu1t1qhncts.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.0xa7kgbuw0i07l44ujmiazs1v.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.1ic2mqya3v3laouyh8018e7yu.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.21d9n7nvjp9whhlnjfwrzcaip.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2chmhzmce29un2p5aqvsy15jh.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2h4lopnp3woikeonplzmhc0nv.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2mju1ukg99b0yv1s0g0opq28d.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2n6t2sx4jts63nobe1ju4xofx.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rhokkseltpqc9andmx6u2r2w.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2rw4yme7h7aehc6u1ma26fxum.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.2zvb2xpkrh4onudn3rzvmu7k4.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3k1vkeh97ivuanpaqm9wnbm35.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mohzrrezerp65vdqoaar8xtd.1uwodqe.rcgu.o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021.3mon2525yms8rau8qxu3n5jd4.1uwodqe.rcgu.o ...\n18.111  collect2         156088 156087   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.113  ld.lld           156091 156088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/heapless-1640e7d816e37021/build_script_build-1640e7d816e37021 ...\n18.114  rust-lld         156091 156088   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUWt5qL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.125  runc             156095 146687   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 --log-format json --systemd-cgroup kill --all 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c 9\n18.145  runc             156120 146687   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 --log-format json --systemd-cgroup delete 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c\n18.175  build-script-bu  156129 155994   0 /target/debug/build/heapless-1640e7d816e37021/build-script-build\n18.180  rustc            156131 155994   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name heapless --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"defmt-03\", \"mpmc_large\", \"portable-atomic\", \"portable-atomic-critical-section\", \"portable-atomic-unsafe-ass -C metadata=81506217a3a7e12c ...\n18.197  cargo            156136 155882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.211  rustc            156137 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.222  rustc            156142 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=8eab25d199e7deb9 ...\n18.232  rustc            156145 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n18.253  cc               156159 156142   0 /tmp/native-trace-155965-1783993104408/shims/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcsi6iI5/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.0co4w98.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n18.254  cc               156160 156159   0 /usr/bin/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcsi6iI5/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.0co4w98.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.0co4w98.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n18.257  collect2         156161 156160   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.258  ld.lld           156162 156161   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b ...\n18.260  rust-lld         156162 156161   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0gX7wj.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.302  build-script-bu  156180 155993   0 /target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build\n18.304  rustc            156181 156180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n18.315  rustc            156183 156180   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_ae266a08b08eb5bb_0 --crate-type=lib --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/fs-err-6e7f7f43f71799c8/out --emit=llvm-ir --target powerpc64le-unknown-linux-gnu -\n18.337  containerd-shim  156194 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3 delete\n18.337  rustc            156193 155993   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_err --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=ea980410505747aa ...\n18.340  runc             156201 156194   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434 --log-format json delete --force 70f36a6dc1c63c1e953b4f2392b2d69f25b02a465d13d123356d8c427b3d434c\n18.374  systemd-sysctl   156212 155732   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth649a077 --prefix=/net/ipv4/neigh/veth649a077 --prefix=/net/ipv6/conf/veth649a077 --prefix=/net/ipv6/neigh/veth649a077\n18.435  rustc            156216 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=8eab25d199e7deb9 ...\n18.466  cc               156242 156216   0 /tmp/native-trace-155882-1783993104292/shims/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n18.468  cc               156249 156242   0 /usr/bin/cc -m64 /target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n18.470  collect2         156253 156249   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.472  ld.lld           156256 156253   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b ...\n18.474  rust-lld         156256 156253   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccs8MLyH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.514  build-script-bu  156298 156136   0 /target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build\n18.516  rustc            156299 156298   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n18.528  rustc            156301 156298   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_77a383603c224a07_0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/fs-err-d223f2b3d73c7254/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n18.548  rustc            156309 156136   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_err --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"io_safety\", \"tokio\")) -C metadata=e5fa82910511c4ea ...\n"
    },
    {
      "argv": [
        "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 151837,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build",
      "pid": 151837,
      "ppid": 151102,
      "root_cargo_pid": 151102,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 151837,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 151840,
      "ppid": 151837,
      "root_cargo_pid": 151102,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 151837,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 151847,
      "ppid": 151837,
      "root_cargo_pid": 151102,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 151837,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 151873,
      "ppid": 151837,
      "root_cargo_pid": 151102,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "slotmap",
      "cwd": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "event_id": "bsrun:d20aa50d73e1f0e5:31fc1c25b134e6d5:0b48ffbf0383fa98",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/slotmap-9cd0fd3344a99352/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
      "out_dir": "/target/debug/build/slotmap-9cd0fd3344a99352/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
      "success": true,
      "target": null,
      "version": "1.0.7",
      "_owner": {
        "crate": "slotmap",
        "version": "1.0.7",
        "package_id": "path+file:///tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7#slotmap@1.0.7",
        "manifest_dir": "/tmp/crate-build-aarch64-r_mh50o6/src/slotmap-1.0.7",
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
      "build_script_root_pid": 151837,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 151840,
      "ppid": 151837,
      "root_cargo_pid": 151102,
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
      "build_script_root_pid": 151837,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 151847,
      "ppid": 151837,
      "root_cargo_pid": 151102,
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
      "build_script_root_pid": 151837,
      "build_script_target_dir": "slotmap-9cd0fd3344a99352",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 151873,
      "ppid": 151837,
      "root_cargo_pid": 151102,
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
