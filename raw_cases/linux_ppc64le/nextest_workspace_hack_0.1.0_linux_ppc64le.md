# `nextest-workspace-hack` `0.1.0`

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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
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
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
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
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-659196-1783995211113494713.map",
  "pid": 659196,
  "ppid": 659177,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-659196-1783995211113494713.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "workspace_root": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
      "name": "nextest-workspace-hack",
      "version": "0.1.0",
      "manifest_path": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0"
    }
  ],
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 659196,
  "ppid": 659177,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:44e554f14977d4d5:8bb8acca13a928fb:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
  "pid": 659196,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:44e554f14977d4d5:6590724fef3adb4c:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
  "pid": 659196,
  "sha256": "38a8a0cd235c3900277a8d7e359ed2d685e125d4befea6f195f488dc8447c5f9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:44e554f14977d4d5:9ab051b770365356:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
  "pid": 659196,
  "sha256": "580b03b7ccac50cea827c37d15a82b3aa07e5ae9d0fd3050913383935dd7cce9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:44e554f14977d4d5:a36103775bba06c6:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
  "pid": 659196,
  "sha256": "cc1071d73958aab5a6c7c2b325e472fb2199f81a20a59e1180aee864097f2cd4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:44e554f14977d4d5:af277d596858f047:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
  "pid": 659196,
  "sha256": "3bd8d1da589b95c04f3157485d2b2b68625ffa9b7b350f6dc4b9d86e5145f705",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:44e554f14977d4d5:c6cec8c464a56b45:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
  "pid": 659196,
  "sha256": "995e4a3cdf16bce2fd1a63469da5ed3fae9708e4be0e6f10037136e838b7771c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "event_id": "used:cc:44e554f14977d4d5:0bee5dfd19e067a4:5a9a44ca5b0349e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
  "pid": 659196,
  "sha256": "275b2c1bb701c27d64e032fe033132eaa178d54a7b50cedf52c875e279f6c4cb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
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
  "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "cargo_pkg_name": "nextest-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "context_path": "/tmp/native-trace-656086-1783995182273/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-656086-1783995182273/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 659196,
  "ppid": 659177,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu",
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
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
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
      "kind": "object",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-659196-1783995211113494713.map",
  "pid": 659196,
  "ppid": 659177,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-659196-1783995211113494713.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
  "parsed_event_count": 482,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 483,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": " conftest.c\n11.471  cc1              659570 659569   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n11.609  cc               659575 659394   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcEqeUbh/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcEqeUbh/symbols.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.0.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.1.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.2.rcgu.o /target/debug/deps/rustcEqeUbh/rmeta.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.2a70930xd5ihj1m6gpj43rkxs.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /target/debug/deps/libheck-68b0ff9b9f8bcb25.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n11.611  cc               659576 659575   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcEqeUbh/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcEqeUbh/symbols.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.0.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.1.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.2.rcgu.o /target/debug/deps/rustcEqeUbh/rmeta.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.2a70930xd5ihj1m6gpj43rkxs.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /target/debug/deps/libheck-68b0ff9b9f8bcb25.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n11.737  rustc            659584 649548   0 \n11.755  rustc            659587 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fancy_regex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"std\" ...\n11.785  cc               659581 659379   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcOF3H9V/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOF3H9V/symbols.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.0.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.1.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.2.rcgu.o /target/debug/deps/rustcOF3H9V/rmeta.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.e6qi66xipcqji4ken8cee50uh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n11.839  cc               659589 659581   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcOF3H9V/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOF3H9V/symbols.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.0.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.1.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.2.rcgu.o /target/debug/deps/rustcOF3H9V/rmeta.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.e6qi66xipcqji4ken8cee50uh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n11.839  collect2         659588 659576   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcEqeUbh/raw-dylibs ...\n11.910  ld.lld           659590 659588   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcEqeUbh/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n11.970  collect2         659592 659589   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOF3H9V/raw-dylibs ...\n11.970  ld.lld           659593 659592   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOF3H9V/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n12.027  rust-lld         659590 659588   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n12.030  rust-lld         659593 659592   0 \n12.263  as               659609 659569   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o conftest.o /tmp/ccD48DNC.s\n12.329  grep             659610 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n12.333  cat              659611 649576   0 /usr/bin/cat conftest.er1\n12.335  mv               659612 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n12.340  rm               659613 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n12.344  cat              659614 649576   0 /usr/bin/cat\n12.351  cat              659615 649576   0 /usr/bin/cat confdefs.h -\n12.356  rm               659616 649576   0 /usr/bin/rm -f conftest.o\n12.361  cc               659618 659617   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n12.364  cc               659619 659618   0 /usr/bin/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n12.368  cc1              659620 659619   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n12.797  riscv64-linux-g  659624 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n12.948  cc1plus          659625 659624   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n12.962  sh               659623 2147557   0 /bin/sh -c which ps\n13.056  which            659623 2147557   0 /usr/bin/which ps\n13.100  sh               659627 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.194  ps               659627 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.409  as               659657 659619   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include --64 -o conftest.o /tmp/ccZRrzcv.s\n13.455  rm               659669 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n13.460  cat              659670 649576   0 /usr/bin/cat confdefs.h -\n13.535  cc               659672 659671   0 /tmp/native-trace-643006-1783995068237/shims/cc -E -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n13.537  cc               659673 659672   0 /usr/bin/cc -E -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n13.631  cc1              659674 659673   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -E -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -mtune=generic -march=x86-64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -dumpbase conftest.c -dumpbase-ext .c ...\n13.742  rm               659676 649576   0 /usr/bin/rm -f conftest.err conftest.i conftest.c\n13.822  cat              659677 649576   0 /usr/bin/cat confdefs.h -\n13.885  rm               659679 649576   0 /usr/bin/rm -f conftest.o conftest\n13.890  cc               659681 659680   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/lib -lexpat\n13.915  aarch64-linux-g  659683 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n13.924  cc1plus          659684 659683   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/ir/type-updating.cpp ...\n13.946  as               659686 651979   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n13.982  rustc            659691 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"perf-backtrack\" ...\n13.989  sh               659693 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n13.992  cpuUsage.sh      659693 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n13.992  cc               659682 659681   0   conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include  -L/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/lib  -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659681-1783995220005074668.map\n13.994  sed              659694 659693   0 \n13.994  rustc            659692 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fancy_regex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"std\" ...\n13.997  cc1              659695 659682   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n14.000  cat              659696 659693   0 /usr/bin/cat /proc/2240539/stat\n14.003  cat              659697 659693   0 /usr/bin/cat /proc/4193716/stat\n14.005  sleep            659699 659693   0 /usr/bin/sleep 1\n14.037  as               659705 659682   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include --64 -o /tmp/ccuRbqt7.o /tmp/ccVDSegg.s\n14.046  collect2         659706 659682   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN6J5KJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n14.046  ld               659707 659706   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN6J5KJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n14.048  ld               659708 659707   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN6J5KJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n14.068  cat              659709 649576   0 /usr/bin/cat conftest.err\n14.071  grep             659711 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n14.074  cat              659712 649576   0 /usr/bin/cat conftest.er1\n14.075  mv               659713 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n14.080  sed              659714 649576   0 /usr/bin/sed s/^/| / conftest.c\n14.085  rm               659715 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n14.088  rm               659716 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n14.095  sed              659720 659718   0 \n14.118  sort             659723 659717   0 /usr/bin/sort\n14.128  runc             659710 653858   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3 --log-format json --systemd-cgroup kill --all 96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3b1f22 9\n14.134  sed              659732 659722   0 /usr/bin/sed -n /^[_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]*_cv_[_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ01\n14.144  sort             659734 649576   0 /usr/bin/sort\n14.149  cat              659735 649576   0 /usr/bin/cat confdefs.h\n14.155  rm               659736 649576   0 /usr/bin/rm -f core *.core core.conftest.*\n14.157  rm               659737 649576   0 /usr/bin/rm -f -r conftest* confdefs.h conf649576*\n14.183  runc             659738 653858   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3 --log-format json --systemd-cgroup delete 96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3b1f22\n14.565  containerd-shim  659746 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3b1f22 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3 delete\n14.573  runc             659754 659746   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3b1f2 --log-format json delete --force 96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3b1f22\n15.006  sed              659762 659693   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.009  cat              659764 659693   0 /usr/bin/cat /proc/2240539/stat\n15.272  sh               659765 659759   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth84a8a11\n15.322  cat              659774 659693   0 /usr/bin/cat /proc/4193716/stat\n15.350  rustc            659775 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prettyplease --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.25/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) -C metadata=262b195b483510c2 ...\n15.352  sed              659779 659765   0 /usr/bin/sed -n s/^driver: //p\n15.354  ethtool          659778 659765   0 /usr/sbin/ethtool -i veth84a8a11\n15.398  rustc            659785 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name synstructure --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/synstructure-0.13.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n15.571  systemd-sysctl   659789 659759   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth84a8a11 --prefix=/net/ipv4/neigh/veth84a8a11 --prefix=/net/ipv6/conf/veth84a8a11 --prefix=/net/ipv6/neigh/veth84a8a11\n16.177  cc               659806 659396   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcpc7DUI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcpc7DUI/symbols.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.0.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.1.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.2.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.3.rcgu.o /target/debug/deps/rustcpc7DUI/rmeta.o /target/debug/deps/num_derive-2e66d8de68040dca.41hzvqn5w44w3gaonbffubmbt.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n16.179  cc               659807 659806   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcpc7DUI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcpc7DUI/symbols.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.0.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.1.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.2.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.3.rcgu.o /target/debug/deps/rustcpc7DUI/rmeta.o /target/debug/deps/num_derive-2e66d8de68040dca.41hzvqn5w44w3gaonbffubmbt.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n16.184  collect2         659808 659807   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXaPD7G.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libnum_derive-2e66d8de68040dca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcpc7DUI/raw-dylibs ...\n16.187  ld.lld           659809 659808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXaPD7G.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libnum_derive-2e66d8de68040dca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcpc7DUI/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.190  rust-lld         659809 659808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXaPD7G.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libnum_derive-2e66d8de68040dca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n16.496  runc             659815 642837   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3a --log-format json --systemd-cgroup kill --all bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3ac214a 9\n16.508  cc               659821 659359   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcoxYtSk/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcoxYtSk/symbols.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.0.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.1.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.2.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.3.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.4.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.5.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.6.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.7.rcgu.o /target/debug/deps/rustcoxYtSk/rmeta.o /target/debug/deps/displaydoc-0b89f0ee18b89456.bkeqq1tkyogd0tnxlux4ksw9x.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib ...\n16.511  cc               659822 659821   0 \n16.515  collect2         659823 659822   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUswwuP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libdisplaydoc-0b89f0ee18b89456.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcoxYtSk/raw-dylibs ...\n16.520  runc             659824 642837   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3a --log-format json --systemd-cgroup delete bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3ac214a\n16.520  ld.lld           659825 659823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUswwuP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdisplaydoc-0b89f0ee18b89456.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcoxYtSk/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.524  rust-lld         659825 659823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUswwuP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdisplaydoc-0b89f0ee18b89456.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n16.532  containerd-shim  659831 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3ac214a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3a delete\n16.542  cargo            659836 657445   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n16.551  as               659837 647627   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/f7deeeb1a9f9c241-table-utils.o /tmp/ccxtFOkG.s\n16.733  rustc            659838 659836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.940  runc             659842 659831   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3ac214 --log-format json delete --force bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3ac214a\n17.200  systemd-sysctl   659872 659791   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth28bccbf --prefix=/net/ipv4/neigh/veth28bccbf --prefix=/net/ipv6/conf/veth28bccbf --prefix=/net/ipv6/neigh/veth28bccbf\n17.565  sh               659894 2147557   0 /bin/sh -c which ps\n17.566  which            659894 2147557   0 /usr/bin/which ps\n17.593  sh               659895 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.655  rustc            659900 659836   0 \n17.655  rustc            659899 659836   0 \n17.655  ps               659895 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.741  rustup           659905 642576   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.122  cc               659925 659924   0 \n18.122  cc               659924 659356   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustc7Ho0F6/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc7Ho0F6/symbols.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.00.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.01.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.02.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.03.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.04.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.05.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.06.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.07.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.08.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.09.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.10.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.11.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.12.rcgu.o /target/debug/deps/rustc7Ho0F6/rmeta.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.0qy67zgyt5vtunkaa89eduk75.rcgu.o ...\n18.164  sh               659930 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.168  cpuUsage.sh      659930 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.171  sed              659931 659930   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.214  collect2         659929 659925   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOx5QwC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerofrom_derive-f87371fc30b4e674.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc7Ho0F6/raw-dylibs ...\n18.235  cat              659932 659930   0 /usr/bin/cat /proc/2240539/stat\n18.238  cat              659933 659930   0 /usr/bin/cat /proc/4193716/stat\n18.240  sleep            659934 659930   0 /usr/bin/sleep 1\n18.293  as               659939 655527   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/f7deeeb1a9f9c241-lubs.o /tmp/ccXEuAB2.s\n18.306  rustc            659940 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name synstructure --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/synstructure-0.13.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n18.311  rustc            659941 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prettyplease --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.25/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) -C metadata=262b195b483510c2 ...\n18.332  rustc            659946 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"perf-backtrack\" ...\n18.341  rustc            659947 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fancy_regex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"std\" ...\n18.495  ld.lld           659966 659929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOx5QwC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-f87371fc30b4e674.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc7Ho0F6/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.497  rust-lld         659966 659929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOx5QwC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-f87371fc30b4e674.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n19.480  sed              659990 659930   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.523  cat              659997 659930   0 /usr/bin/cat /proc/2240539/stat\n19.527  cat              659999 659930   0 /usr/bin/cat /proc/4193716/stat\n19.624  cc               660001 659355   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcs8Awgd/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcs8Awgd/symbols.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.00.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.01.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.02.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.03.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.04.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.05.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.06.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.07.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.08.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.09.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.10.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.11.rcgu.o /target/debug/deps/rustcs8Awgd/rmeta.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.cehp8jpec2o8fho91irs509jv.rcgu.o -Wl,--as-needed ...\n19.632  rustc            660006 659836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n19.640  cc               660007 660001   0 \n19.649  collect2         660009 660007   0 \n19.653  ld.lld           660010 660009   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczIiCyQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-b88cad70b1eb6b8a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcs8Awgd/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n19.779  rust-lld         660010 660009   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczIiCyQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-b88cad70b1eb6b8a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n19.786  16               660017 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n19.807  frpc             660017 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n20.004  as               660032 654756   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n20.346  as               660061 657676   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/f7deeeb1a9f9c241-stack-utils.o /tmp/ccrqCHfy.s\n20.353  riscv64-linux-g  660062 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n20.361  cc1plus          660063 660062   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n20.403  cc               660064 659358   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcHy3Sy1/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHy3Sy1/symbols.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.09.rcgu.o /target/debug/deps/rustcHy3Sy1/rmeta.o /target/debug/deps/zerovec_derive-f191f7679debf83c.0x4sh6z27gp4j24jxrhafizpk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib ...\n20.412  cc               660067 660064   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcHy3Sy1/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHy3Sy1/symbols.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.09.rcgu.o /target/debug/deps/rustcHy3Sy1/rmeta.o /target/debug/deps/zerovec_derive-f191f7679debf83c.0x4sh6z27gp4j24jxrhafizpk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib ...\n20.427  collect2         660068 660067   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoeRgp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerovec_derive-f191f7679debf83c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcHy3Sy1/raw-dylibs ...\n20.428  ld.lld           660069 660068   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoeRgp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-f191f7679debf83c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcHy3Sy1/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.430  rust-lld         660069 660068   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoeRgp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-f191f7679debf83c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.546  rustc            660077 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerofrom --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerofrom-0.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"derive\" --check-cfg cfg(docsrs,test) ...\n20.649  as               660085 651686   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n20.798  rustc            660098 660096   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.798  cross            660096 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.804  rustc            660098 660096   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.852  aarch64-linux-g  660113 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n20.854  cc1plus          660114 660113   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n20.901  rustc            660115 660096   0 /home/xmoe/.cargo/bin/rustc -vV\n21.055  rustc            660115 660096   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.156  cargo            660153 660096   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.183  riscv64-linux-g  660163 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n21.183  cargo            660153 660096   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.190  cc1plus          660164 660163   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n21.801  rustc            660171 660153   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.868  riscv64-linux-g  660184 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n21.870  cc1plus          660185 660184   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n22.115  rustc            660188 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name yoke --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yoke-0.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n22.235  rustc            660195 660153   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.378  rustc            660206 660153   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.475  aarch64-linux-g  660214 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n22.478  cc1plus          660215 660214   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/LoopInvariantCodeMotion ...\n22.563  sh               660219 2147557   0 /bin/sh -c which ps\n22.565  which            660219 2147557   0 /usr/bin/which ps\n22.568  sh               660221 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.570  ps               660221 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.784  sh               660229 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n22.786  cpuUsage.sh      660229 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n22.788  sed              660230 660229   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n22.793  cat              660231 660229   0 /usr/bin/cat /proc/2240539/stat\n22.795  cat              660232 660229   0 /usr/bin/cat /proc/4193716/stat\n22.797  sleep            660233 660229   0 /usr/bin/sleep 1\n23.000  rustc            660238 660096   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.000  rustc            660238 660096   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.007  rustc            660251 660096   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.027  rustc            660251 660096   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.037  docker           660263 660096   0 /usr/bin/docker --help\n23.070  docker           660274 660096   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.143  runc             660283 1599     0 /usr/bin/runc --version\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 659282,
  "build_script_target_dir": "nextest-workspace-hack-6f004b1889039ee0",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build",
  "pid": 659282,
  "ppid": 659116,
  "root_cargo_pid": 659116,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "_build_script_out_dir": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/out"
}
```

#### Record 16

```json
{
  "crate": "nextest-workspace-hack",
  "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "event_id": "bsrun:98d1b3f607b0f273:e19ba20bdaa1db6c:87f55097ebf11c6d",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
  "out_dir": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
  "success": true,
  "target": null,
  "version": "0.1.0",
  "_owner": {
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:13:50.846848+00:00",
  "crate": "nextest-workspace-hack",
  "version": "0.1.0",
  "architecture": "ppc64le",
  "duration_seconds": 60.84688854776323,
  "trace_record_count": 16,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "manifest_path": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 13,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
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
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "workspace_root": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
          "name": "nextest-workspace-hack",
          "version": "0.1.0",
          "manifest_path": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0"
        }
      ],
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 659196,
      "ppid": 659177,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:44e554f14977d4d5:8bb8acca13a928fb:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
      "pid": 659196,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:44e554f14977d4d5:6590724fef3adb4c:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
      "pid": 659196,
      "sha256": "38a8a0cd235c3900277a8d7e359ed2d685e125d4befea6f195f488dc8447c5f9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:44e554f14977d4d5:9ab051b770365356:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
      "pid": 659196,
      "sha256": "580b03b7ccac50cea827c37d15a82b3aa07e5ae9d0fd3050913383935dd7cce9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:44e554f14977d4d5:a36103775bba06c6:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
      "pid": 659196,
      "sha256": "cc1071d73958aab5a6c7c2b325e472fb2199f81a20a59e1180aee864097f2cd4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:44e554f14977d4d5:af277d596858f047:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
      "pid": 659196,
      "sha256": "3bd8d1da589b95c04f3157485d2b2b68625ffa9b7b350f6dc4b9d86e5145f705",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:44e554f14977d4d5:c6cec8c464a56b45:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
      "pid": 659196,
      "sha256": "995e4a3cdf16bce2fd1a63469da5ed3fae9708e4be0e6f10037136e838b7771c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "event_id": "used:cc:44e554f14977d4d5:0bee5dfd19e067a4:5a9a44ca5b0349e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
      "pid": 659196,
      "sha256": "275b2c1bb701c27d64e032fe033132eaa178d54a7b50cedf52c875e279f6c4cb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
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
      "output": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "cargo_pkg_name": "nextest-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "context_path": "/tmp/native-trace-656086-1783995182273/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-656086-1783995182273/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 659196,
      "ppid": 659177,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu",
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
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
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/rustcxatiQu/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.0uiv7kmyt6n1kysh04clft4j7.1w568n8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.314m32cldtim18jdct4idpyqd.1w568n8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.41g0g9oe56erzh6voawtzioob.1w568n8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.6wx1b65ymx6ykezwzl2wkd0nn.1w568n8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.cafru4ktskrwnxh45seiqne6a.1w568n8.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0",
          "kind": "object",
          "path": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build_script_build-6f004b1889039ee0.8do2cs51mmzpwwopugfzumtly.1w568n8.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-659196-1783995211113494713.map",
      "pid": 659196,
      "ppid": 659177,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-659196-1783995211113494713.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
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
      "parsed_event_count": 482,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 483,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": " conftest.c\n11.471  cc1              659570 659569   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n11.609  cc               659575 659394   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcEqeUbh/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcEqeUbh/symbols.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.0.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.1.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.2.rcgu.o /target/debug/deps/rustcEqeUbh/rmeta.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.2a70930xd5ihj1m6gpj43rkxs.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /target/debug/deps/libheck-68b0ff9b9f8bcb25.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n11.611  cc               659576 659575   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcEqeUbh/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcEqeUbh/symbols.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.0.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.1.rcgu.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.substrait_validator_derive.754b52c1eb0b7569-cgu.2.rcgu.o /target/debug/deps/rustcEqeUbh/rmeta.o /target/debug/deps/substrait_validator_derive-c6881f41d39a1361.2a70930xd5ihj1m6gpj43rkxs.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /target/debug/deps/libheck-68b0ff9b9f8bcb25.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n11.737  rustc            659584 649548   0 \n11.755  rustc            659587 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fancy_regex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"std\" ...\n11.785  cc               659581 659379   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcOF3H9V/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOF3H9V/symbols.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.0.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.1.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.2.rcgu.o /target/debug/deps/rustcOF3H9V/rmeta.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.e6qi66xipcqji4ken8cee50uh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n11.839  cc               659589 659581   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcOF3H9V/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcOF3H9V/symbols.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.0.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.1.rcgu.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.icu_provider_macros.b20789cb8eebce16-cgu.2.rcgu.o /target/debug/deps/rustcOF3H9V/rmeta.o /target/debug/deps/icu_provider_macros-c2c067d0314674b7.e6qi66xipcqji4ken8cee50uh.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n11.839  collect2         659588 659576   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcEqeUbh/raw-dylibs ...\n11.910  ld.lld           659590 659588   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcEqeUbh/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n11.970  collect2         659592 659589   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOF3H9V/raw-dylibs ...\n11.970  ld.lld           659593 659592   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoWkLVe.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libicu_provider_macros-c2c067d0314674b7.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcOF3H9V/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n12.027  rust-lld         659590 659588   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXgaq7c.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libsubstrait_validator_derive-c6881f41d39a1361.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n12.030  rust-lld         659593 659592   0 \n12.263  as               659609 659569   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/freetype-sys-0a1cecd000bd86d3/out/include/freetype2 --64 -o conftest.o /tmp/ccD48DNC.s\n12.329  grep             659610 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n12.333  cat              659611 649576   0 /usr/bin/cat conftest.er1\n12.335  mv               659612 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n12.340  rm               659613 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n12.344  cat              659614 649576   0 /usr/bin/cat\n12.351  cat              659615 649576   0 /usr/bin/cat confdefs.h -\n12.356  rm               659616 649576   0 /usr/bin/rm -f conftest.o\n12.361  cc               659618 659617   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n12.364  cc               659619 659618   0 /usr/bin/cc -c -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n12.368  cc1              659620 659619   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n12.797  riscv64-linux-g  659624 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n12.948  cc1plus          659625 659624   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n12.962  sh               659623 2147557   0 /bin/sh -c which ps\n13.056  which            659623 2147557   0 /usr/bin/which ps\n13.100  sh               659627 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.194  ps               659627 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n13.409  as               659657 659619   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include --64 -o conftest.o /tmp/ccZRrzcv.s\n13.455  rm               659669 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n13.460  cat              659670 649576   0 /usr/bin/cat confdefs.h -\n13.535  cc               659672 659671   0 /tmp/native-trace-643006-1783995068237/shims/cc -E -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n13.537  cc               659673 659672   0 /usr/bin/cc -E -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c\n13.631  cc1              659674 659673   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -E -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -mtune=generic -march=x86-64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -dumpbase conftest.c -dumpbase-ext .c ...\n13.742  rm               659676 649576   0 /usr/bin/rm -f conftest.err conftest.i conftest.c\n13.822  cat              659677 649576   0 /usr/bin/cat confdefs.h -\n13.885  rm               659679 649576   0 /usr/bin/rm -f conftest.o conftest\n13.890  cc               659681 659680   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include conftest.c -L/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/lib -lexpat\n13.915  aarch64-linux-g  659683 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n13.924  cc1plus          659684 659683   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/ir/type-updating.cpp ...\n13.946  as               659686 651979   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n13.982  rustc            659691 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"perf-backtrack\" ...\n13.989  sh               659693 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n13.992  cpuUsage.sh      659693 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n13.992  cc               659682 659681   0   conftest -fPIC -I/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include  -L/target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/lib  -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-659681-1783995220005074668.map\n13.994  sed              659694 659693   0 \n13.994  rustc            659692 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fancy_regex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"std\" ...\n13.997  cc1              659695 659682   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection ...\n14.000  cat              659696 659693   0 /usr/bin/cat /proc/2240539/stat\n14.003  cat              659697 659693   0 /usr/bin/cat /proc/4193716/stat\n14.005  sleep            659699 659693   0 /usr/bin/sleep 1\n14.037  as               659705 659682   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/expat-sys-11d92e639b6c6bba/out/include --64 -o /tmp/ccuRbqt7.o /tmp/ccVDSegg.s\n14.046  collect2         659706 659682   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN6J5KJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n14.046  ld               659707 659706   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN6J5KJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n14.048  ld               659708 659707   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccN6J5KJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n14.068  cat              659709 649576   0 /usr/bin/cat conftest.err\n14.071  grep             659711 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n14.074  cat              659712 649576   0 /usr/bin/cat conftest.er1\n14.075  mv               659713 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n14.080  sed              659714 649576   0 /usr/bin/sed s/^/| / conftest.c\n14.085  rm               659715 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n14.088  rm               659716 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n14.095  sed              659720 659718   0 \n14.118  sort             659723 659717   0 /usr/bin/sort\n14.128  runc             659710 653858   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3 --log-format json --systemd-cgroup kill --all 96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3b1f22 9\n14.134  sed              659732 659722   0 /usr/bin/sed -n /^[_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]*_cv_[_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ01\n14.144  sort             659734 649576   0 /usr/bin/sort\n14.149  cat              659735 649576   0 /usr/bin/cat confdefs.h\n14.155  rm               659736 649576   0 /usr/bin/rm -f core *.core core.conftest.*\n14.157  rm               659737 649576   0 /usr/bin/rm -f -r conftest* confdefs.h conf649576*\n14.183  runc             659738 653858   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3 --log-format json --systemd-cgroup delete 96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3b1f22\n14.565  containerd-shim  659746 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3b1f22 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3 delete\n14.573  runc             659754 659746   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3b1f2 --log-format json delete --force 96c09ebc90b3bffa44fd2661e9ceceef14ca8d0abf2164411cb977ab7b3b1f22\n15.006  sed              659762 659693   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.009  cat              659764 659693   0 /usr/bin/cat /proc/2240539/stat\n15.272  sh               659765 659759   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth84a8a11\n15.322  cat              659774 659693   0 /usr/bin/cat /proc/4193716/stat\n15.350  rustc            659775 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prettyplease --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.25/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) -C metadata=262b195b483510c2 ...\n15.352  sed              659779 659765   0 /usr/bin/sed -n s/^driver: //p\n15.354  ethtool          659778 659765   0 /usr/sbin/ethtool -i veth84a8a11\n15.398  rustc            659785 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name synstructure --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/synstructure-0.13.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n15.571  systemd-sysctl   659789 659759   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth84a8a11 --prefix=/net/ipv4/neigh/veth84a8a11 --prefix=/net/ipv6/conf/veth84a8a11 --prefix=/net/ipv6/neigh/veth84a8a11\n16.177  cc               659806 659396   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcpc7DUI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcpc7DUI/symbols.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.0.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.1.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.2.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.3.rcgu.o /target/debug/deps/rustcpc7DUI/rmeta.o /target/debug/deps/num_derive-2e66d8de68040dca.41hzvqn5w44w3gaonbffubmbt.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n16.179  cc               659807 659806   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcpc7DUI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcpc7DUI/symbols.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.0.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.1.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.2.rcgu.o /target/debug/deps/num_derive-2e66d8de68040dca.num_derive.9abd02bcca933ac1-cgu.3.rcgu.o /target/debug/deps/rustcpc7DUI/rmeta.o /target/debug/deps/num_derive-2e66d8de68040dca.41hzvqn5w44w3gaonbffubmbt.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib /target/debug/deps/libunicode_ident-71134888432ae9cf.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r ...\n16.184  collect2         659808 659807   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXaPD7G.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libnum_derive-2e66d8de68040dca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcpc7DUI/raw-dylibs ...\n16.187  ld.lld           659809 659808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXaPD7G.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libnum_derive-2e66d8de68040dca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcpc7DUI/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.190  rust-lld         659809 659808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXaPD7G.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libnum_derive-2e66d8de68040dca.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n16.496  runc             659815 642837   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3a --log-format json --systemd-cgroup kill --all bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3ac214a 9\n16.508  cc               659821 659359   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcoxYtSk/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcoxYtSk/symbols.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.0.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.1.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.2.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.3.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.4.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.5.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.6.rcgu.o /target/debug/deps/displaydoc-0b89f0ee18b89456.displaydoc.9e088a48c93d846b-cgu.7.rcgu.o /target/debug/deps/rustcoxYtSk/rmeta.o /target/debug/deps/displaydoc-0b89f0ee18b89456.bkeqq1tkyogd0tnxlux4ksw9x.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib /target/debug/deps/libquote-ca63141b22f34600.rlib /target/debug/deps/libproc_macro2-4ef55736ad416d23.rlib ...\n16.511  cc               659822 659821   0 \n16.515  collect2         659823 659822   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUswwuP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libdisplaydoc-0b89f0ee18b89456.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcoxYtSk/raw-dylibs ...\n16.520  runc             659824 642837   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3a --log-format json --systemd-cgroup delete bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3ac214a\n16.520  ld.lld           659825 659823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUswwuP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdisplaydoc-0b89f0ee18b89456.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcoxYtSk/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.524  rust-lld         659825 659823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUswwuP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdisplaydoc-0b89f0ee18b89456.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n16.532  containerd-shim  659831 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3ac214a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3a delete\n16.542  cargo            659836 657445   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n16.551  as               659837 647627   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/f7deeeb1a9f9c241-table-utils.o /tmp/ccxtFOkG.s\n16.733  rustc            659838 659836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.940  runc             659842 659831   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3ac214 --log-format json delete --force bc131565fa97136d6e4dcdf477e510a2ac546c2f70a924099b64ae58f3ac214a\n17.200  systemd-sysctl   659872 659791   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth28bccbf --prefix=/net/ipv4/neigh/veth28bccbf --prefix=/net/ipv6/conf/veth28bccbf --prefix=/net/ipv6/neigh/veth28bccbf\n17.565  sh               659894 2147557   0 /bin/sh -c which ps\n17.566  which            659894 2147557   0 /usr/bin/which ps\n17.593  sh               659895 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.655  rustc            659900 659836   0 \n17.655  rustc            659899 659836   0 \n17.655  ps               659895 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.741  rustup           659905 642576   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.122  cc               659925 659924   0 \n18.122  cc               659924 659356   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustc7Ho0F6/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc7Ho0F6/symbols.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.00.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.01.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.02.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.03.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.04.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.05.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.06.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.07.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.08.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.09.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.10.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.11.rcgu.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.zerofrom_derive.d1449044eb30010a-cgu.12.rcgu.o /target/debug/deps/rustc7Ho0F6/rmeta.o /target/debug/deps/zerofrom_derive-f87371fc30b4e674.0qy67zgyt5vtunkaa89eduk75.rcgu.o ...\n18.164  sh               659930 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.168  cpuUsage.sh      659930 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.171  sed              659931 659930   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.214  collect2         659929 659925   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOx5QwC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerofrom_derive-f87371fc30b4e674.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc7Ho0F6/raw-dylibs ...\n18.235  cat              659932 659930   0 /usr/bin/cat /proc/2240539/stat\n18.238  cat              659933 659930   0 /usr/bin/cat /proc/4193716/stat\n18.240  sleep            659934 659930   0 /usr/bin/sleep 1\n18.293  as               659939 655527   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/f7deeeb1a9f9c241-lubs.o /tmp/ccXEuAB2.s\n18.306  rustc            659940 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name synstructure --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/synstructure-0.13.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n18.311  rustc            659941 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prettyplease --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.25/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) -C metadata=262b195b483510c2 ...\n18.332  rustc            659946 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"perf-backtrack\" ...\n18.341  rustc            659947 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fancy_regex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"perf\" --cfg feature=\"std\" ...\n18.495  ld.lld           659966 659929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOx5QwC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-f87371fc30b4e674.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc7Ho0F6/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.497  rust-lld         659966 659929   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOx5QwC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-f87371fc30b4e674.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n19.480  sed              659990 659930   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.523  cat              659997 659930   0 /usr/bin/cat /proc/2240539/stat\n19.527  cat              659999 659930   0 /usr/bin/cat /proc/4193716/stat\n19.624  cc               660001 659355   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcs8Awgd/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcs8Awgd/symbols.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.00.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.01.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.02.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.03.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.04.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.05.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.06.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.07.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.08.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.09.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.10.rcgu.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.yoke_derive.3fd06628d7413bd-cgu.11.rcgu.o /target/debug/deps/rustcs8Awgd/rmeta.o /target/debug/deps/yoke_derive-b88cad70b1eb6b8a.cehp8jpec2o8fho91irs509jv.rcgu.o -Wl,--as-needed ...\n19.632  rustc            660006 659836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n19.640  cc               660007 660001   0 \n19.649  collect2         660009 660007   0 \n19.653  ld.lld           660010 660009   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczIiCyQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-b88cad70b1eb6b8a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcs8Awgd/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n19.779  rust-lld         660010 660009   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczIiCyQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-b88cad70b1eb6b8a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n19.786  16               660017 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n19.807  frpc             660017 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n20.004  as               660032 654756   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n20.346  as               660061 657676   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -W -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/f7deeeb1a9f9c241-stack-utils.o /tmp/ccrqCHfy.s\n20.353  riscv64-linux-g  660062 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n20.361  cc1plus          660063 660062   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n20.403  cc               660064 659358   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcHy3Sy1/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHy3Sy1/symbols.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.09.rcgu.o /target/debug/deps/rustcHy3Sy1/rmeta.o /target/debug/deps/zerovec_derive-f191f7679debf83c.0x4sh6z27gp4j24jxrhafizpk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib ...\n20.412  cc               660067 660064   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcHy3Sy1/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHy3Sy1/symbols.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-f191f7679debf83c.zerovec_derive.3d6916eae07a57f4-cgu.09.rcgu.o /target/debug/deps/rustcHy3Sy1/rmeta.o /target/debug/deps/zerovec_derive-f191f7679debf83c.0x4sh6z27gp4j24jxrhafizpk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-cfffd490ceb44c80.rlib ...\n20.427  collect2         660068 660067   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoeRgp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerovec_derive-f191f7679debf83c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcHy3Sy1/raw-dylibs ...\n20.428  ld.lld           660069 660068   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoeRgp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-f191f7679debf83c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcHy3Sy1/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n20.430  rust-lld         660069 660068   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpoeRgp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-f191f7679debf83c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n20.546  rustc            660077 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerofrom --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerofrom-0.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"derive\" --check-cfg cfg(docsrs,test) ...\n20.649  as               660085 651686   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d ...\n20.798  rustc            660098 660096   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.798  cross            660096 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.804  rustc            660098 660096   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.852  aarch64-linux-g  660113 625892   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include ...\n20.854  cc1plus          660114 660113   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/cxxbridge/crate -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out -I /tmp/crate-build-aarch64-m04n5ok3/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n20.901  rustc            660115 660096   0 /home/xmoe/.cargo/bin/rustc -vV\n21.055  rustc            660115 660096   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.156  cargo            660153 660096   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.183  riscv64-linux-g  660163 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n21.183  cargo            660153 660096   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.190  cc1plus          660164 660163   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n21.801  rustc            660171 660153   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.868  riscv64-linux-g  660184 626155   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out ...\n21.870  cc1plus          660185 660184   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out/cxxbridge/crate -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-4382e3808ca76fa6/out -I /tmp/crate-build-riscv64-dhrev5rb/src/wasm-opt-sys-0.116.0/binaryen/third_party/llvm-project/include -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D ...\n22.115  rustc            660188 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name yoke --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yoke-0.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n22.235  rustc            660195 660153   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n22.378  rustc            660206 660153   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n22.475  aarch64-linux-g  660214 629824   0 /usr/bin/aarch64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -Wall -Wextra ...\n22.478  cc1plus          660215 660214   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/include -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-b9765cd3b71f93d7/out -imultiarch aarch64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D NDEBUG /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/passes/LoopInvariantCodeMotion ...\n22.563  sh               660219 2147557   0 /bin/sh -c which ps\n22.565  which            660219 2147557   0 /usr/bin/which ps\n22.568  sh               660221 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.570  ps               660221 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n22.784  sh               660229 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n22.786  cpuUsage.sh      660229 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n22.788  sed              660230 660229   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n22.793  cat              660231 660229   0 /usr/bin/cat /proc/2240539/stat\n22.795  cat              660232 660229   0 /usr/bin/cat /proc/4193716/stat\n22.797  sleep            660233 660229   0 /usr/bin/sleep 1\n23.000  rustc            660238 660096   0 /home/xmoe/.cargo/bin/rustc --print target-list\n23.000  rustc            660238 660096   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n23.007  rustc            660251 660096   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n23.027  rustc            660251 660096   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n23.037  docker           660263 660096   0 /usr/bin/docker --help\n23.070  docker           660274 660096   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n23.143  runc             660283 1599     0 /usr/bin/runc --version\n"
    },
    {
      "argv": [
        "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 659282,
      "build_script_target_dir": "nextest-workspace-hack-6f004b1889039ee0",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build",
      "pid": 659282,
      "ppid": 659116,
      "root_cargo_pid": 659116,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "nextest-workspace-hack",
      "cwd": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "event_id": "bsrun:98d1b3f607b0f273:e19ba20bdaa1db6c:87f55097ebf11c6d",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
      "out_dir": "/target/debug/build/nextest-workspace-hack-6f004b1889039ee0/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
      "success": true,
      "target": null,
      "version": "0.1.0",
      "_owner": {
        "crate": "nextest-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0#nextest-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-ofksk57r/src/nextest-workspace-hack-0.1.0",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 2511,
    "crate": "nextest-workspace-hack",
    "version": "0.1.0",
    "crate_id": "683061",
    "version_id": "637337",
    "downloads": 4967084,
    "cumulative_downloads": 104774238593,
    "cumulative_share_of_global": 0.3917266903569677,
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
