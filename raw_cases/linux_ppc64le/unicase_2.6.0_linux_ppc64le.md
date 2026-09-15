# `unicase` `2.6.0`

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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
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
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo",
    "/target/debug/build/unicase-846ae3192758395d",
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
      "directory": "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-77819-1783992870518064301.map",
  "pid": 77819,
  "ppid": 77619,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-77819-1783992870518064301.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "workspace_root": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
      "name": "unicase",
      "version": "2.6.0",
      "manifest_path": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
      "name": "version_check",
      "version": "0.9.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5"
    }
  ],
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 77819,
  "ppid": 77619,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicase",
  "cargo_pkg_version": "2.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "event_id": "used:cc:3c4c70f355b96716:5b540cfb6290cd74:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
  "pid": 77819,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicase",
  "cargo_pkg_version": "2.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "event_id": "used:cc:3c4c70f355b96716:d6dad3deaac2cddf:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
  "pid": 77819,
  "sha256": "38717bb516b662577e1cabc7610e2755b5de50187a1d4d22dc42f17e4e9b66d3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicase",
  "cargo_pkg_version": "2.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "event_id": "used:cc:3c4c70f355b96716:e818a994a62413b7:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
  "pid": 77819,
  "sha256": "d5a37a64dcb80871df96ba5607ec8cf38c0aa3dc90f143cc2b5b426b5b1581ca",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicase",
  "cargo_pkg_version": "2.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "event_id": "used:cc:3c4c70f355b96716:abc909ec3810c722:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
  "pid": 77819,
  "sha256": "535c70c4ff409c320fa4f0adc43ad705e0e26400a6b2883dc37f9e04158dae00",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicase",
  "cargo_pkg_version": "2.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "event_id": "used:cc:3c4c70f355b96716:5c16a3a2c208d9c8:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
  "pid": 77819,
  "sha256": "8cf0319502ddf27d890ec4bf2f38b258ed27e60a8381d34b1f7fc4818ad30dd9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicase",
  "cargo_pkg_version": "2.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "event_id": "used:cc:3c4c70f355b96716:4ccdec5e247fcfe7:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
  "pid": 77819,
  "sha256": "cf04f376ee902d4d9a8c9a64cf5c6dfa5d647ac04e88299783f26b59e7023019",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicase",
  "cargo_pkg_version": "2.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "event_id": "used:cc:3c4c70f355b96716:b13429a8114812a3:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
  "pid": 77819,
  "sha256": "57cb448a35a6ddd4381107ff2a1b6799de90c8e7f5f8500bfee46428b000060e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "unicase",
  "cargo_pkg_version": "2.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "event_id": "used:cc:3c4c70f355b96716:f96676b9876f4775:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
  "pid": 77819,
  "sha256": "91b0ef9692d5720a82899f6f887251aafecf6cc42b3b1d1802ab1ef32be9d37f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
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
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "cargo_pkg_name": "unicase",
  "cargo_pkg_version": "2.6.0",
  "context_path": "/tmp/native-trace-76737-1783992867759/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-76737-1783992867759/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 77819,
  "ppid": 77619,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo",
    "/target/debug/build/unicase-846ae3192758395d",
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
      "directory": "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-77819-1783992870518064301.map",
  "pid": 77819,
  "ppid": 77619,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-77819-1783992870518064301.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
    "source": "cargo_manifest_dir"
  }
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

#### Record 15

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 1472,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1474,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "ult\" --cfg ...\n11.587  runc             81586  74391    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 --log-format json --systemd-cgroup kill --all f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e 9\n11.605  runc             81592  74391    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 --log-format json --systemd-cgroup delete f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e\n11.784  containerd-shim  81598  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 delete\n11.786  runc             81605  81598    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6 --log-format json delete --force f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e\n11.827  systemd-sysctl   81610  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b6db40 --prefix=/net/ipv4/neigh/veth5b6db40 --prefix=/net/ipv6/conf/veth5b6db40 --prefix=/net/ipv6/neigh/veth5b6db40\n12.949  sh               81612  2147557   0 /bin/sh -c which ps\n12.951  which            81612  2147557   0 /usr/bin/which ps\n12.954  sh               81613  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.955  ps               81613  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.983  runc             81614  70730    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 --log-format json --systemd-cgroup kill --all 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966 9\n12.986  sh               81620  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n12.988  cpuUsage.sh      81620  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n12.990  sed              81621  81620    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n12.992  cat              81622  81620    0 /usr/bin/cat /proc/2240539/stat\n12.993  runc             81623  70730    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 --log-format json --systemd-cgroup delete 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966\n12.994  cat              81624  81620    0 /usr/bin/cat /proc/4193716/stat\n12.996  sleep            81630  81620    0 /usr/bin/sleep 1\n13.201  containerd-shim  81632  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 delete\n13.204  runc             81639  81632    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef96 --log-format json delete --force 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966\n13.231  runc             81644  70770    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a --log-format json --systemd-cgroup kill --all 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b 9\n13.241  runc             81650  70770    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a --log-format json --systemd-cgroup delete 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b\n13.245  systemd-sysctl   81656  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf8b421b --prefix=/net/ipv4/neigh/vethf8b421b --prefix=/net/ipv6/conf/vethf8b421b --prefix=/net/ipv6/neigh/vethf8b421b\n13.448  containerd-shim  81657  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a delete\n13.451  runc             81664  81657    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901 --log-format json delete --force 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b\n13.490  systemd-sysctl   81669  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth77ef5ac --prefix=/net/ipv4/neigh/veth77ef5ac --prefix=/net/ipv6/conf/veth77ef5ac --prefix=/net/ipv6/neigh/veth77ef5ac\n13.998  sed              81670  81620    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.002  cat              81671  81620    0 /usr/bin/cat /proc/2240539/stat\n14.003  runc             81672  75033    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dd --log-format json --systemd-cgroup kill --all 159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dda8473 9\n14.004  cat              81674  81620    0 /usr/bin/cat /proc/4193716/stat\n14.022  runc             81681  75033    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dd --log-format json --systemd-cgroup delete 159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dda8473\n14.221  containerd-shim  81687  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dda8473 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dd delete\n14.224  runc             81693  81687    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dda847 --log-format json delete --force 159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dda8473\n14.273  sh               81701  81543    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth9a96efa\n14.275  ethtool          81702  81701    0 /usr/sbin/ethtool -i veth9a96efa\n14.276  sed              81703  81701    0 /usr/bin/sed -n s/^driver: //p\n14.282  systemd-sysctl   81706  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9a96efa --prefix=/net/ipv4/neigh/veth9a96efa --prefix=/net/ipv6/conf/veth9a96efa --prefix=/net/ipv6/neigh/veth9a96efa\n15.059  cross            81707  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.060  rustc            81710  81707    0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.067  rustc            81710  81707    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.071  cross            81720  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.073  cross            81723  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n15.073  rustc            81724  81720    0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.075  rustc            81726  81723    0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.080  rustc            81724  81720    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.081  16               81747  1        0 /proc/self/fd/16 --deserialize 147 --log-level info --log-target journal-or-kmsg\n15.081  rustc            81726  81723    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.083  rustc            81748  81707    0 /home/xmoe/.cargo/bin/rustc -vV\n15.085  16               81749  1        0 /proc/self/fd/16 --deserialize 161 --log-level info --log-target journal-or-kmsg\n15.090  rustc            81748  81707    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.095  rustc            81764  81723    0 /home/xmoe/.cargo/bin/rustc -vV\n15.095  rustc            81765  81720    0 /home/xmoe/.cargo/bin/rustc -vV\n15.102  cargo            81784  81707    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.103  rustc            81764  81723    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.103  rustc            81765  81720    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.109  cargo            81784  81707    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.116  cargo            81795  81720    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.117  cargo            81796  81723    0 \n15.122  cargo            81795  81720    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.123  cargo            81796  81723    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.124  rustc            81813  81784    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.136  rustc            81815  81795    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.137  rustc            81816  81796    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.137  rustc            81817  81784    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.148  rustc            81823  81796    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.149  rustc            81824  81795    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.151  rustc            81825  81784    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.163  rustc            81836  81795    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.164  rustc            81835  81796    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.233  drkonqi-coredum  81749  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 894-81719-0\n15.237  systemd-coredum  81747  1        0 /usr/lib/systemd/systemd-coredump\n15.241  rustc            81844  81784    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.258  rustc            81846  81723    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.259  rustc            81847  81720    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.262  rustc            81856  81707    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.265  rustc            81846  81723    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.265  rustc            81847  81720    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.271  rustc            81856  81707    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.279  docker           81879  81723    0 /usr/bin/docker --help\n15.282  docker           81884  81720    0 /usr/bin/docker --help\n15.285  docker           81894  81707    0 /usr/bin/docker --help\n15.295  docker           81914  81723    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.299  docker           81920  81720    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.301  docker           81921  81707    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.311  runc             81948  1599     0 /usr/bin/runc --version\n15.314  runc             81954  1599     0 /usr/bin/runc --version\n15.315  docker-init      81955  1599     0 /usr/bin/docker-init --version\n15.317  runc             81958  1599     0 /usr/bin/runc --version\n15.317  docker           81967  81723    0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.319  docker-init      81968  1599     0 /usr/bin/docker-init --version\n15.319  docker-init      81969  1599     0 /usr/bin/docker-init --version\n15.321  docker           81975  81707    0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.323  docker           81978  81720    0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.334  runc             82003  1599     0 /usr/bin/runc --version\n15.336  runc             82009  1599     0 /usr/bin/runc --version\n15.337  runc             82010  1599     0 /usr/bin/runc --version\n15.339  docker-init      82020  1599     0 /usr/bin/docker-init --version\n15.341  docker-init      82022  1599     0 /usr/bin/docker-init --version\n15.342  docker-init      82023  1599     0 /usr/bin/docker-init --version\n15.369  rustup           82025  81723    0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.369  rustup           82027  81707    0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.371  rustup           82028  81720    0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.377  rustup           82059  81723    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.377  rustup           82058  81707    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.379  rustup           82061  81720    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.407  rustup           82086  81723    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.410  rustup           82087  81720    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.410  rustup           82088  81707    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.441  uname            82113  81723    0 /usr/bin/uname -r\n15.442  uname            82114  81707    0 /usr/bin/uname -r\n15.443  uname            82115  81720    0 /usr/bin/uname -r\n15.463  docker           82116  81723    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.464  docker           82117  81720    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.465  docker           82118  81707    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.517  systemd-sysctl   82158  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb84c177 --prefix=/net/ipv4/neigh/vethb84c177 --prefix=/net/ipv6/conf/vethb84c177 --prefix=/net/ipv6/neigh/vethb84c177\n15.517  systemd-sysctl   82159  81553    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd0dedbd --prefix=/net/ipv4/neigh/vethd0dedbd --prefix=/net/ipv6/conf/vethd0dedbd --prefix=/net/ipv6/neigh/vethd0dedbd\n15.544  systemd-sysctl   82191  82170    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethce348f7 --prefix=/net/ipv4/neigh/vethce348f7 --prefix=/net/ipv6/conf/vethce348f7 --prefix=/net/ipv6/neigh/vethce348f7\n15.544  systemd-sysctl   82192  82190    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth341f062 --prefix=/net/ipv4/neigh/veth341f062 --prefix=/net/ipv6/conf/veth341f062 --prefix=/net/ipv6/neigh/veth341f062\n15.550  systemd-sysctl   82194  82182    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7961395 --prefix=/net/ipv4/neigh/veth7961395 --prefix=/net/ipv6/conf/veth7961395 --prefix=/net/ipv6/neigh/veth7961395\n15.550  systemd-sysctl   82193  82175    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7e5b7f7 --prefix=/net/ipv4/neigh/veth7e5b7f7 --prefix=/net/ipv6/conf/veth7e5b7f7 --prefix=/net/ipv6/neigh/veth7e5b7f7\n15.554  containerd-shim  82195  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc34866649 start\n15.559  containerd-shim  82202  82195    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc34866649 -address /var/run/docker/containerd/containerd.sock\n15.566  runc             82212  82202    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc348 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc348 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc348 a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc34866649\n15.573  exe              82220  82212    0 /proc/self/exe init\n15.610  exe              82229  82212    0 /proc/1599/exe -exec-root=/var/run/docker a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc34866649 d7da31e8f8e1\n15.628  exe              82237  1599     0 /proc/self/exe /var/run/docker/netns/84f798673455 all false\n15.663  containerd-shim  82257  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195acc4c start\n15.665  containerd-shim  82261  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878a17d8 start\n15.666  containerd-shim  82268  82257    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195acc4c -address /var/run/docker/containerd/containerd.sock\n15.668  containerd-shim  82276  82261    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878a17d8 -address /var/run/docker/containerd/containerd.sock\n15.670  runc             82289  82268    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195 4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195acc4c\n15.673  runc             82297  82276    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878 632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878a17d8\n15.673  9                82298  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n15.676  abrt-server      82304  1118     0 /usr/bin/abrt-server -s\n15.676  exe              82306  82289    0 /proc/self/exe init\n15.678  exe              82310  82297    0 /proc/self/exe init\n15.681  runc             82311  82202    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc348 --log-format json --systemd-cgroup start a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc34866649\n15.683  drkonqi-coredum  82298  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n15.687  sh               82223  82202    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.688  cargo            82325  82223    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.690  cross            82332  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n15.692  rustc            82335  82332    0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.697  rustc            82335  82332    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.702  cargo-native-tr  82325  82223    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.703  abrt-handle-eve  82344  82304    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:34:45.534888-73924\n15.704  exe              82345  82289    0 /proc/1599/exe -exec-root=/var/run/docker 4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195acc4c d7da31e8f8e1\n15.707  exe              82350  82297    0 /proc/1599/exe -exec-root=/var/run/docker 632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878a17d8 d7da31e8f8e1\n15.707  cargo            82347  82325    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.712  rustc            82362  82332    0 /home/xmoe/.cargo/bin/rustc -vV\n15.718  rustc            82362  82332    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.718  sh               82376  82344    0 /bin/sh -c abrt-action-save-package-data\\n\n15.720  abrt-action-sav  82376  82344    0 /usr/bin/abrt-action-save-package-data\n15.722  rustc            82378  82347    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.730  cargo            82381  82332    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.731  exe              82384  1599     0 /proc/self/exe /var/run/docker/netns/b86332df6078 all false\n15.733  exe              82394  1599     0 /proc/self/exe /var/run/docker/netns/24346d755d9c all false\n15.736  rustc            82387  82347    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.737  cargo            82381  82332    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.750  rustc            82420  82381    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.753  execsnoop        82426  82325    0 /usr/local/bin/execsnoop -t\n15.753  python3          82426  82325    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.760  rustc            82430  82381    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.771  rustc            82434  82381    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.773  sh               82435  82344    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n15.774  cut              82437  82435    0 /usr/bin/cut -d: -f1\n15.774  cat              82438  82436    0 /usr/bin/cat uid\n15.775  getent           82436  82435    0 /usr/bin/getent passwd 1000\n15.777  lscpu            82439  82435    0 /usr/bin/lscpu\n15.783  runc             82443  82276    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878 --log-format json --systemd-cgroup start 632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878a17d8\n15.788  sh               82326  82276    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.790  cargo            82450  82326    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n15.790  sh               82451  82344    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n15.792  runlevel         82452  82451    0 /usr/bin/runlevel\n15.800  runc             82453  82268    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195 --log-format json --systemd-cgroup start 4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195acc4c\n15.801  sh               82459  82344    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n15.802  cargo-native-tr  82450  82326    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n15.803  grep             82460  82459    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n15.804  grep             82461  82459    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n15.805  grep             82463  82459    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n15.806  sh               82318  82268    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.806  cargo            82462  82450    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.807  cargo            82464  82318    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.807  abrt-action-cor  82465  82459    0 /usr/libexec/abrt-action-coredump -x\n15.818  cargo-native-tr  82464  82318    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.818  rustc            82466  82462    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.822  cargo            82467  82464    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.831  rustc            82469  82462    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.833  rustc            82470  82467    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.844  rustc            82475  82467    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.865  abrt-action-gen  82479  82459    0 /usr/bin/abrt-action-generate-core-backtrace\n15.868  rustc            82480  82381    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.886  execsnoop        82483  82450    0 /usr/local/bin/execsnoop -t\n15.886  rustc            82482  82332    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.887  python3          82483  82450    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.889  execsnoop        82486  82464    0 /usr/local/bin/execsnoop -t\n15.889  python3          82486  82464    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.893  rustc            82482  82332    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.905  docker           82500  82332    0 /usr/bin/docker --help\n15.910  abrt-action-ana  82506  82459    0 /usr/bin/abrt-action-analyze-vulnerability\n15.911  eu-readelf       82509  82508    0 /usr/bin/eu-readelf -n coredump\n15.912  sed              82511  82508    0 /usr/bin/sed s/[^0-9]//g\n15.912  grep             82510  82508    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n15.914  gdb              82518  82515    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n15.919  docker           82519  82332    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.929  iconv            82530  82518    0 /usr/bin/iconv -l\n15.931  runc             82531  1599     0 /usr/bin/runc --version\n15.934  docker-init      82537  1599     0 /usr/bin/docker-init --version\n15.935  docker           82548  82332    0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.948  runc             82560  1599     0 /usr/bin/runc --version\n15.952  docker-init      82566  1599     0 /usr/bin/docker-init --version\n15.979  rustup           82570  82332    0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.985  rustup           82579  82332    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.009  rustup           82588  82332    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.017  abrt-action-ana  82597  82459    0 /usr/bin/abrt-action-analyze-c\n16.028  eu-unstrip       82598  82597    0 /usr/bin/eu-unstrip --core=./coredump -n\n16.034  uname            82599  82332    0 /usr/bin/uname -r\n16.045  abrt-action-lis  82600  82459    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n16.052  docker           82601  82332    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.090  systemd-sysctl   82614  82182    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe016e0c --prefix=/net/ipv4/neigh/vethe016e0c --prefix=/net/ipv6/conf/vethe016e0c --prefix=/net/ipv6/neigh/vethe016e0c\n16.091  systemd-sysctl   82613  82175    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4698508 --prefix=/net/ipv4/neigh/veth4698508 --prefix=/net/ipv6/conf/veth4698508 --prefix=/net/ipv6/neigh/veth4698508\n16.102  cat              82616  82615    0 /usr/bin/cat executable\n16.104  cat              82617  82615    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:34:45.534888-73924/uid\n16.106  journalctl       82618  82615    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n16.108  containerd-shim  82619  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6ee5aa6 start\n16.111  containerd-shim  82626  82619    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6ee5aa6 -address /var/run/docker/containerd/containerd.sock\n16.114  runc             82635  82626    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6e f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6ee5aa6\n16.119  abrt-action-cor  82641  82459    0 /usr/libexec/abrt-action-coredump -r\n16.120  exe              82643  82635    0 /proc/self/exe init\n16.153  exe              82653  82635    0 /proc/1599/exe -exec-root=/var/run/docker f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6ee5aa6 d7da31e8f8e1\n16.169  abrt-handle-eve  82660  82304    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.173  exe              82662  1599     0 /proc/self/exe /var/run/docker/netns/7722c4bb484e all false\n16.182  sh               82671  82660    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n16.183  dbus-send        82671  82660    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.186  sh               82674  82660    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n16.187  abrt-action-not  82675  82674    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.225  runc             82681  82626    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6e --log-format json --systemd-cgroup start f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6ee5aa6\n16.230  sh               82647  82626    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.231  cargo            82687  82647    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n16.242  cargo-native-tr  82687  82647    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n16.243  16               82691  1        0 /proc/self/fd/16 --deserialize 137 --log-level info --log-target journal-or-kmsg\n16.247  cargo            82692  82687    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.256  abrt-dbus        82691  1        0 /usr/sbin/abrt-dbus -t133\n16.259  rustc            82693  82692    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.270  rustc            82695  82692    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.284  sh               82703  82675    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n16.285  reporter-system  82703  82675    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n16.288  execsnoop        82704  82687    0 /usr/local/bin/execsnoop -t\n16.289  python3          82704  82687    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.176  git              82710  2235138   0 /usr/bin/git config --get commit.template\n17.192  git              82711  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n17.210  git              82712  2235138   0 /usr/bin/git status -z -uall\n17.227  git              82713  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n17.466  runc             82714  3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process3716857347 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n17.471  exe              82722  82714    0 /proc/self/exe init\n17.492  etcdctl          82724  82714    0 /usr/local/bin/etcdctl endpoint health\n17.669  git              82739  2235138   0 /usr/bin/git worktree list --porcelain\n17.823  cargo            82740  82450    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.837  rustc            82741  82740    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.856  rustc            82747  82740    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n17.949  sh               82751  2147557   0 /bin/sh -c which ps\n17.951  which            82751  2147557   0 /usr/bin/which ps\n17.953  sh               82752  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.955  ps               82752  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.986  sh               82753  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.987  cpuUsage.sh      82753  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.989  sed              82754  82753    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.991  cat              82755  82753    0 /usr/bin/cat /proc/2240539/stat\n17.993  cat              82756  82753    0 /usr/bin/cat /proc/4193716/stat\n17.994  sleep            82757  82753    0 /usr/bin/sleep 1\n18.024  cargo            82758  82325    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.037  rustc            82759  82758    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.057  rustc            82775  82758    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.058  rustc            82777  82758    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0b3033f3338346bd ...\n18.058  rustc            82776  82758    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name core_foundation_sys --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/core-foundation-sys-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"link\" --check-cfg cfg(docsrs,test) ...\n18.124  cc               82868  82747    0 /tmp/native-trace-82450-1783992885668/shims/cc -m64 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/rustcZwBNCf/symbols.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.03ed02i528934v0hmjzocfwy6.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.07qzmpbdqvjqtgmk5iovi03ou.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0a1j7385zj1dnhdx7mgyaeio9.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0c1fv380bielmakxlryin6ddh.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0irnafe09lfeepm33cjnk80z7.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0q8txkg232l1ajzji3wkdgb8e.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0zavkj1xbxp9olmdycqikzrir.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.16hi055u99lagkwidvsdzc2sz.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.18b7gboh39s3ctndr53z6aalf.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1p3fgzo92ubc6cnk1n5tkgwjg.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1sb4yftkyxs9zho1hsrjatb05.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.20eryb3ybfvz4hg0psuxgkf5u.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.25ywm0zgjx7xfg3rezsq6nln4.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.29mnwj50d939ns67hhgpyrv5k.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2e1ckot5ze1ifqjv1w5websvh.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fd1wt3koiv5gt7i5yip4o1d2.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fn9c1cehny0t2a52g5zem5xs.1k2zhvw.rcgu.o ...\n18.127  cc               82882  82868    0 /usr/bin/cc -m64 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/rustcZwBNCf/symbols.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.03ed02i528934v0hmjzocfwy6.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.07qzmpbdqvjqtgmk5iovi03ou.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0a1j7385zj1dnhdx7mgyaeio9.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0c1fv380bielmakxlryin6ddh.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0irnafe09lfeepm33cjnk80z7.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0q8txkg232l1ajzji3wkdgb8e.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0zavkj1xbxp9olmdycqikzrir.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.16hi055u99lagkwidvsdzc2sz.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.18b7gboh39s3ctndr53z6aalf.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1p3fgzo92ubc6cnk1n5tkgwjg.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1sb4yftkyxs9zho1hsrjatb05.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.20eryb3ybfvz4hg0psuxgkf5u.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.25ywm0zgjx7xfg3rezsq6nln4.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.29mnwj50d939ns67hhgpyrv5k.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2e1ckot5ze1ifqjv1w5websvh.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fd1wt3koiv5gt7i5yip4o1d2.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fn9c1cehny0t2a52g5zem5xs.1k2zhvw.rcgu.o ...\n18.132  collect2         82892  82882    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc36jZUl.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.134  cross            82895  4193716   0 /home/xmoe/.local/bin/cross build --target powerpc64le-unknown-linux-gnu\n18.136  ld.lld           82901  82892    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc36jZUl.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87 ...\n18.138  rust-lld         82901  82892    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc36jZUl.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.138  rustc            82899  82895    0 /home/xmoe/.cargo/bin/rustc --print target-list\n18.144  rustc            82899  82895    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n18.148  cc               82913  82777    0 /tmp/native-trace-82325-1783992885567/shims/cc -m64 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/rustckoJguu/symbols.o /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.08xsa41xf04swsmxtcva73iaz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.0h37aofhusrl4ripqg5df6866.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.0hqnjb2lez043n75qc4hkofgz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1b69m4dtr7j1wasbmbsnybw4v.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1ej7r5av2lea3vkph6f110nrk.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1t53yq88i9ftx6feewl08g0dz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1zbka6gqhcyemmty761qxtym3.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.2ftt27iiruuk7o5k3dt3cbt3j.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.2tbyiomy52jcb282p4oe5zp5g.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.3nby01yamainihvmyj0ioqpkw.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.4n7inizkjgf7pljvn13ubv7pz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.4oc1flbmcwlkpvd79362sfc9b.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.525gzycdwgigqmfme4nu54l22.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.52fram4mu3meh083fc317sfld.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.5pv5utk8xw6gxmbckwpji5hva.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.63f2ls55pdw6ah7kmlysq29zx.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.6pebuju04o30e6qjf9fcbkc9q.0w05 ...\n18.150  cc               82914  82913    0 /usr/bin/cc -m64 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/rustckoJguu/symbols.o /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.08xsa41xf04swsmxtcva73iaz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.0h37aofhusrl4ripqg5df6866.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.0hqnjb2lez043n75qc4hkofgz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1b69m4dtr7j1wasbmbsnybw4v.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1ej7r5av2lea3vkph6f110nrk.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1t53yq88i9ftx6feewl08g0dz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1zbka6gqhcyemmty761qxtym3.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.2ftt27iiruuk7o5k3dt3cbt3j.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.2tbyiomy52jcb282p4oe5zp5g.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.3nby01yamainihvmyj0ioqpkw.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.4n7inizkjgf7pljvn13ubv7pz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.4oc1flbmcwlkpvd79362sfc9b.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.525gzycdwgigqmfme4nu54l22.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.52fram4mu3meh083fc317sfld.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.5pv5utk8xw6gxmbckwpji5hva.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.63f2ls55pdw6ah7kmlysq29zx.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.6pebuju04o30e6qjf9fcbkc9q.0w05 ...\n18.154  collect2         82931  82914    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Sx94R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.156  ld.lld           82933  82931    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Sx94R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22 ...\n18.159  rust-lld         82933  82931    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Sx94R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.163  rustc            82937  82895    0 /home/xmoe/.cargo/bin/rustc -vV\n18.170  rustc            82937  82895    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.186  cargo            82964  82895    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n18.193  cargo            82964  82895    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n18.209  rustc            82977  82964    0 \n18.221  rustc            82980  82964    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.233  build-script-bu  82985  82758    0 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build-script-build\n18.236  rustc            82986  82964    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.239  build-script-bu  82989  82740    0 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build-script-build\n18.240  cc               82987  82775    0 /tmp/native-trace-82325-1783992885567/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcafM8VX/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.241  cc               82990  82987    0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcafM8VX/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.243  rustc            82991  82989    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.246  collect2         82992  82990    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb7csLU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.247  ld.lld           82996  82992    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb7csLU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n18.249  rust-lld         82996  82992    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb7csLU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.257  cargo            83001  82464    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.260  rustc            83000  82740    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n"
}
```

#### Record 16

```json
{
  "argv": [
    "/target/debug/build/unicase-846ae3192758395d/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 78065,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/unicase-846ae3192758395d/build-script-build",
  "pid": 78065,
  "ppid": 77319,
  "root_cargo_pid": 77319,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_build_script_out_dir": "/target/debug/build/unicase-846ae3192758395d/out"
}
```

#### Record 17

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 78065,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 78066,
  "ppid": 78065,
  "root_cargo_pid": 77319,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_build_script_out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 18

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 78065,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 78076,
  "ppid": 78065,
  "root_cargo_pid": 77319,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_build_script_out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_cwd_recovered_from_build_script_run": true
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
  "build_script_root_pid": 78065,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 78115,
  "ppid": 78065,
  "root_cargo_pid": 77319,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_build_script_out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
  "build_script_root_pid": 78065,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 78144,
  "ppid": 78065,
  "root_cargo_pid": 77319,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_build_script_out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 21

```json
{
  "crate": "unicase",
  "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "event_id": "bsrun:f939409873bf8eac:f45bd61f2d409c5e:13a358b6d37bd762",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/unicase-846ae3192758395d/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
  "out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
  "success": true,
  "target": null,
  "version": "2.6.0",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 78065,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 78066,
  "ppid": 78065,
  "root_cargo_pid": 77319,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
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
  "build_script_root_pid": 78065,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 78076,
  "ppid": 78065,
  "root_cargo_pid": 77319,
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
  "build_script_root_pid": 78065,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 78115,
  "ppid": 78065,
  "root_cargo_pid": 77319,
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
  "build_script_root_pid": 78065,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 78144,
  "ppid": 78065,
  "root_cargo_pid": 77319,
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
  "time": "2026-07-14T01:34:48.452092+00:00",
  "crate": "unicase",
  "version": "2.6.0",
  "architecture": "ppc64le",
  "duration_seconds": 25.12696365173906,
  "trace_record_count": 21,
  "trace_owner_summary": {
    "owner_package_count": 2,
    "owner_packages": [
      {
        "crate": "version_check",
        "version": "0.9.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml"
      },
      {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "manifest_path": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 14,
    "unattributed_event_count": 7,
    "owners": [
      {
        "crate": "unicase",
        "version": "2.6.0",
        "event_count": 14,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 8,
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
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "workspace_root": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
          "name": "unicase",
          "version": "2.6.0",
          "manifest_path": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
          "name": "version_check",
          "version": "0.9.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5"
        }
      ],
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 77819,
      "ppid": 77619,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicase",
      "cargo_pkg_version": "2.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "event_id": "used:cc:3c4c70f355b96716:5b540cfb6290cd74:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
      "pid": 77819,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicase",
      "cargo_pkg_version": "2.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "event_id": "used:cc:3c4c70f355b96716:d6dad3deaac2cddf:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
      "pid": 77819,
      "sha256": "38717bb516b662577e1cabc7610e2755b5de50187a1d4d22dc42f17e4e9b66d3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicase",
      "cargo_pkg_version": "2.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "event_id": "used:cc:3c4c70f355b96716:e818a994a62413b7:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
      "pid": 77819,
      "sha256": "d5a37a64dcb80871df96ba5607ec8cf38c0aa3dc90f143cc2b5b426b5b1581ca",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicase",
      "cargo_pkg_version": "2.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "event_id": "used:cc:3c4c70f355b96716:abc909ec3810c722:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
      "pid": 77819,
      "sha256": "535c70c4ff409c320fa4f0adc43ad705e0e26400a6b2883dc37f9e04158dae00",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicase",
      "cargo_pkg_version": "2.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "event_id": "used:cc:3c4c70f355b96716:5c16a3a2c208d9c8:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
      "pid": 77819,
      "sha256": "8cf0319502ddf27d890ec4bf2f38b258ed27e60a8381d34b1f7fc4818ad30dd9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicase",
      "cargo_pkg_version": "2.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "event_id": "used:cc:3c4c70f355b96716:4ccdec5e247fcfe7:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
      "pid": 77819,
      "sha256": "cf04f376ee902d4d9a8c9a64cf5c6dfa5d647ac04e88299783f26b59e7023019",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicase",
      "cargo_pkg_version": "2.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "event_id": "used:cc:3c4c70f355b96716:b13429a8114812a3:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
      "pid": 77819,
      "sha256": "57cb448a35a6ddd4381107ff2a1b6799de90c8e7f5f8500bfee46428b000060e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "unicase",
      "cargo_pkg_version": "2.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "event_id": "used:cc:3c4c70f355b96716:f96676b9876f4775:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
      "pid": 77819,
      "sha256": "91b0ef9692d5720a82899f6f887251aafecf6cc42b3b1d1802ab1ef32be9d37f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
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
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "cargo_pkg_name": "unicase",
      "cargo_pkg_version": "2.6.0",
      "context_path": "/tmp/native-trace-76737-1783992867759/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-76737-1783992867759/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 77819,
      "ppid": 77619,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo",
        "/target/debug/build/unicase-846ae3192758395d",
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
          "directory": "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/rustc7x8eXo/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.13fhm7e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.13fhm7e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.13fhm7e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.13fhm7e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.13fhm7e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.13fhm7e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.13fhm7e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.4.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-77819-1783992870518064301.map",
      "pid": 77819,
      "ppid": 77619,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-77819-1783992870518064301.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
      "parsed_event_count": 1472,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1474,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "ult\" --cfg ...\n11.587  runc             81586  74391    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 --log-format json --systemd-cgroup kill --all f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e 9\n11.605  runc             81592  74391    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 --log-format json --systemd-cgroup delete f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e\n11.784  containerd-shim  81598  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 delete\n11.786  runc             81605  81598    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6 --log-format json delete --force f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e\n11.827  systemd-sysctl   81610  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b6db40 --prefix=/net/ipv4/neigh/veth5b6db40 --prefix=/net/ipv6/conf/veth5b6db40 --prefix=/net/ipv6/neigh/veth5b6db40\n12.949  sh               81612  2147557   0 /bin/sh -c which ps\n12.951  which            81612  2147557   0 /usr/bin/which ps\n12.954  sh               81613  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.955  ps               81613  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.983  runc             81614  70730    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 --log-format json --systemd-cgroup kill --all 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966 9\n12.986  sh               81620  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n12.988  cpuUsage.sh      81620  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n12.990  sed              81621  81620    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n12.992  cat              81622  81620    0 /usr/bin/cat /proc/2240539/stat\n12.993  runc             81623  70730    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 --log-format json --systemd-cgroup delete 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966\n12.994  cat              81624  81620    0 /usr/bin/cat /proc/4193716/stat\n12.996  sleep            81630  81620    0 /usr/bin/sleep 1\n13.201  containerd-shim  81632  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 delete\n13.204  runc             81639  81632    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef96 --log-format json delete --force 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966\n13.231  runc             81644  70770    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a --log-format json --systemd-cgroup kill --all 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b 9\n13.241  runc             81650  70770    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a --log-format json --systemd-cgroup delete 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b\n13.245  systemd-sysctl   81656  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf8b421b --prefix=/net/ipv4/neigh/vethf8b421b --prefix=/net/ipv6/conf/vethf8b421b --prefix=/net/ipv6/neigh/vethf8b421b\n13.448  containerd-shim  81657  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a delete\n13.451  runc             81664  81657    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901 --log-format json delete --force 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b\n13.490  systemd-sysctl   81669  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth77ef5ac --prefix=/net/ipv4/neigh/veth77ef5ac --prefix=/net/ipv6/conf/veth77ef5ac --prefix=/net/ipv6/neigh/veth77ef5ac\n13.998  sed              81670  81620    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n14.002  cat              81671  81620    0 /usr/bin/cat /proc/2240539/stat\n14.003  runc             81672  75033    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dd --log-format json --systemd-cgroup kill --all 159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dda8473 9\n14.004  cat              81674  81620    0 /usr/bin/cat /proc/4193716/stat\n14.022  runc             81681  75033    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dd --log-format json --systemd-cgroup delete 159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dda8473\n14.221  containerd-shim  81687  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dda8473 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dd delete\n14.224  runc             81693  81687    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dda847 --log-format json delete --force 159fe611292e9deca0ff8e4e5220fb30d45ba52fccee7b84e4d1e0d08dda8473\n14.273  sh               81701  81543    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth9a96efa\n14.275  ethtool          81702  81701    0 /usr/sbin/ethtool -i veth9a96efa\n14.276  sed              81703  81701    0 /usr/bin/sed -n s/^driver: //p\n14.282  systemd-sysctl   81706  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9a96efa --prefix=/net/ipv4/neigh/veth9a96efa --prefix=/net/ipv6/conf/veth9a96efa --prefix=/net/ipv6/neigh/veth9a96efa\n15.059  cross            81707  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.060  rustc            81710  81707    0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.067  rustc            81710  81707    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.071  cross            81720  4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.073  cross            81723  4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n15.073  rustc            81724  81720    0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.075  rustc            81726  81723    0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.080  rustc            81724  81720    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.081  16               81747  1        0 /proc/self/fd/16 --deserialize 147 --log-level info --log-target journal-or-kmsg\n15.081  rustc            81726  81723    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.083  rustc            81748  81707    0 /home/xmoe/.cargo/bin/rustc -vV\n15.085  16               81749  1        0 /proc/self/fd/16 --deserialize 161 --log-level info --log-target journal-or-kmsg\n15.090  rustc            81748  81707    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.095  rustc            81764  81723    0 /home/xmoe/.cargo/bin/rustc -vV\n15.095  rustc            81765  81720    0 /home/xmoe/.cargo/bin/rustc -vV\n15.102  cargo            81784  81707    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.103  rustc            81764  81723    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.103  rustc            81765  81720    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.109  cargo            81784  81707    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.116  cargo            81795  81720    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.117  cargo            81796  81723    0 \n15.122  cargo            81795  81720    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.123  cargo            81796  81723    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.124  rustc            81813  81784    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.136  rustc            81815  81795    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.137  rustc            81816  81796    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.137  rustc            81817  81784    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.148  rustc            81823  81796    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.149  rustc            81824  81795    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.151  rustc            81825  81784    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.163  rustc            81836  81795    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.164  rustc            81835  81796    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.233  drkonqi-coredum  81749  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 894-81719-0\n15.237  systemd-coredum  81747  1        0 /usr/lib/systemd/systemd-coredump\n15.241  rustc            81844  81784    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.258  rustc            81846  81723    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.259  rustc            81847  81720    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.262  rustc            81856  81707    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.265  rustc            81846  81723    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.265  rustc            81847  81720    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.271  rustc            81856  81707    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.279  docker           81879  81723    0 /usr/bin/docker --help\n15.282  docker           81884  81720    0 /usr/bin/docker --help\n15.285  docker           81894  81707    0 /usr/bin/docker --help\n15.295  docker           81914  81723    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.299  docker           81920  81720    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.301  docker           81921  81707    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.311  runc             81948  1599     0 /usr/bin/runc --version\n15.314  runc             81954  1599     0 /usr/bin/runc --version\n15.315  docker-init      81955  1599     0 /usr/bin/docker-init --version\n15.317  runc             81958  1599     0 /usr/bin/runc --version\n15.317  docker           81967  81723    0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.319  docker-init      81968  1599     0 /usr/bin/docker-init --version\n15.319  docker-init      81969  1599     0 /usr/bin/docker-init --version\n15.321  docker           81975  81707    0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.323  docker           81978  81720    0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.334  runc             82003  1599     0 /usr/bin/runc --version\n15.336  runc             82009  1599     0 /usr/bin/runc --version\n15.337  runc             82010  1599     0 /usr/bin/runc --version\n15.339  docker-init      82020  1599     0 /usr/bin/docker-init --version\n15.341  docker-init      82022  1599     0 /usr/bin/docker-init --version\n15.342  docker-init      82023  1599     0 /usr/bin/docker-init --version\n15.369  rustup           82025  81723    0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.369  rustup           82027  81707    0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.371  rustup           82028  81720    0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.377  rustup           82059  81723    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.377  rustup           82058  81707    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.379  rustup           82061  81720    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.407  rustup           82086  81723    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.410  rustup           82087  81720    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.410  rustup           82088  81707    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.441  uname            82113  81723    0 /usr/bin/uname -r\n15.442  uname            82114  81707    0 /usr/bin/uname -r\n15.443  uname            82115  81720    0 /usr/bin/uname -r\n15.463  docker           82116  81723    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.464  docker           82117  81720    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.465  docker           82118  81707    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.517  systemd-sysctl   82158  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb84c177 --prefix=/net/ipv4/neigh/vethb84c177 --prefix=/net/ipv6/conf/vethb84c177 --prefix=/net/ipv6/neigh/vethb84c177\n15.517  systemd-sysctl   82159  81553    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd0dedbd --prefix=/net/ipv4/neigh/vethd0dedbd --prefix=/net/ipv6/conf/vethd0dedbd --prefix=/net/ipv6/neigh/vethd0dedbd\n15.544  systemd-sysctl   82191  82170    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethce348f7 --prefix=/net/ipv4/neigh/vethce348f7 --prefix=/net/ipv6/conf/vethce348f7 --prefix=/net/ipv6/neigh/vethce348f7\n15.544  systemd-sysctl   82192  82190    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth341f062 --prefix=/net/ipv4/neigh/veth341f062 --prefix=/net/ipv6/conf/veth341f062 --prefix=/net/ipv6/neigh/veth341f062\n15.550  systemd-sysctl   82194  82182    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7961395 --prefix=/net/ipv4/neigh/veth7961395 --prefix=/net/ipv6/conf/veth7961395 --prefix=/net/ipv6/neigh/veth7961395\n15.550  systemd-sysctl   82193  82175    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7e5b7f7 --prefix=/net/ipv4/neigh/veth7e5b7f7 --prefix=/net/ipv6/conf/veth7e5b7f7 --prefix=/net/ipv6/neigh/veth7e5b7f7\n15.554  containerd-shim  82195  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc34866649 start\n15.559  containerd-shim  82202  82195    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc34866649 -address /var/run/docker/containerd/containerd.sock\n15.566  runc             82212  82202    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc348 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc348 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc348 a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc34866649\n15.573  exe              82220  82212    0 /proc/self/exe init\n15.610  exe              82229  82212    0 /proc/1599/exe -exec-root=/var/run/docker a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc34866649 d7da31e8f8e1\n15.628  exe              82237  1599     0 /proc/self/exe /var/run/docker/netns/84f798673455 all false\n15.663  containerd-shim  82257  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195acc4c start\n15.665  containerd-shim  82261  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878a17d8 start\n15.666  containerd-shim  82268  82257    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195acc4c -address /var/run/docker/containerd/containerd.sock\n15.668  containerd-shim  82276  82261    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878a17d8 -address /var/run/docker/containerd/containerd.sock\n15.670  runc             82289  82268    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195 4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195acc4c\n15.673  runc             82297  82276    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878 632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878a17d8\n15.673  9                82298  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n15.676  abrt-server      82304  1118     0 /usr/bin/abrt-server -s\n15.676  exe              82306  82289    0 /proc/self/exe init\n15.678  exe              82310  82297    0 /proc/self/exe init\n15.681  runc             82311  82202    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc348 --log-format json --systemd-cgroup start a713c5c0d2320f165d017a7947dcc8ca6ac651abacb8956fb88e32dc34866649\n15.683  drkonqi-coredum  82298  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n15.687  sh               82223  82202    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.688  cargo            82325  82223    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.690  cross            82332  4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n15.692  rustc            82335  82332    0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.697  rustc            82335  82332    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.702  cargo-native-tr  82325  82223    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.703  abrt-handle-eve  82344  82304    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:34:45.534888-73924\n15.704  exe              82345  82289    0 /proc/1599/exe -exec-root=/var/run/docker 4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195acc4c d7da31e8f8e1\n15.707  exe              82350  82297    0 /proc/1599/exe -exec-root=/var/run/docker 632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878a17d8 d7da31e8f8e1\n15.707  cargo            82347  82325    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.712  rustc            82362  82332    0 /home/xmoe/.cargo/bin/rustc -vV\n15.718  rustc            82362  82332    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.718  sh               82376  82344    0 /bin/sh -c abrt-action-save-package-data\\n\n15.720  abrt-action-sav  82376  82344    0 /usr/bin/abrt-action-save-package-data\n15.722  rustc            82378  82347    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.730  cargo            82381  82332    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.731  exe              82384  1599     0 /proc/self/exe /var/run/docker/netns/b86332df6078 all false\n15.733  exe              82394  1599     0 /proc/self/exe /var/run/docker/netns/24346d755d9c all false\n15.736  rustc            82387  82347    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.737  cargo            82381  82332    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.750  rustc            82420  82381    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.753  execsnoop        82426  82325    0 /usr/local/bin/execsnoop -t\n15.753  python3          82426  82325    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.760  rustc            82430  82381    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.771  rustc            82434  82381    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.773  sh               82435  82344    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n15.774  cut              82437  82435    0 /usr/bin/cut -d: -f1\n15.774  cat              82438  82436    0 /usr/bin/cat uid\n15.775  getent           82436  82435    0 /usr/bin/getent passwd 1000\n15.777  lscpu            82439  82435    0 /usr/bin/lscpu\n15.783  runc             82443  82276    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878 --log-format json --systemd-cgroup start 632bed93ae38103f913a50592fedf41a55604fca02800f066dc26937878a17d8\n15.788  sh               82326  82276    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.790  cargo            82450  82326    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n15.790  sh               82451  82344    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n15.792  runlevel         82452  82451    0 /usr/bin/runlevel\n15.800  runc             82453  82268    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195 --log-format json --systemd-cgroup start 4a674d2bb739efcf2827200618a139f42748655a209cf0a0fc2baed8195acc4c\n15.801  sh               82459  82344    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n15.802  cargo-native-tr  82450  82326    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n15.803  grep             82460  82459    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n15.804  grep             82461  82459    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n15.805  grep             82463  82459    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n15.806  sh               82318  82268    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.806  cargo            82462  82450    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.807  cargo            82464  82318    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.807  abrt-action-cor  82465  82459    0 /usr/libexec/abrt-action-coredump -x\n15.818  cargo-native-tr  82464  82318    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.818  rustc            82466  82462    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.822  cargo            82467  82464    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.831  rustc            82469  82462    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.833  rustc            82470  82467    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.844  rustc            82475  82467    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.865  abrt-action-gen  82479  82459    0 /usr/bin/abrt-action-generate-core-backtrace\n15.868  rustc            82480  82381    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.886  execsnoop        82483  82450    0 /usr/local/bin/execsnoop -t\n15.886  rustc            82482  82332    0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.887  python3          82483  82450    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.889  execsnoop        82486  82464    0 /usr/local/bin/execsnoop -t\n15.889  python3          82486  82464    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.893  rustc            82482  82332    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.905  docker           82500  82332    0 /usr/bin/docker --help\n15.910  abrt-action-ana  82506  82459    0 /usr/bin/abrt-action-analyze-vulnerability\n15.911  eu-readelf       82509  82508    0 /usr/bin/eu-readelf -n coredump\n15.912  sed              82511  82508    0 /usr/bin/sed s/[^0-9]//g\n15.912  grep             82510  82508    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n15.914  gdb              82518  82515    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n15.919  docker           82519  82332    0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.929  iconv            82530  82518    0 /usr/bin/iconv -l\n15.931  runc             82531  1599     0 /usr/bin/runc --version\n15.934  docker-init      82537  1599     0 /usr/bin/docker-init --version\n15.935  docker           82548  82332    0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.948  runc             82560  1599     0 /usr/bin/runc --version\n15.952  docker-init      82566  1599     0 /usr/bin/docker-init --version\n15.979  rustup           82570  82332    0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.985  rustup           82579  82332    0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.009  rustup           82588  82332    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.017  abrt-action-ana  82597  82459    0 /usr/bin/abrt-action-analyze-c\n16.028  eu-unstrip       82598  82597    0 /usr/bin/eu-unstrip --core=./coredump -n\n16.034  uname            82599  82332    0 /usr/bin/uname -r\n16.045  abrt-action-lis  82600  82459    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n16.052  docker           82601  82332    0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.090  systemd-sysctl   82614  82182    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe016e0c --prefix=/net/ipv4/neigh/vethe016e0c --prefix=/net/ipv6/conf/vethe016e0c --prefix=/net/ipv6/neigh/vethe016e0c\n16.091  systemd-sysctl   82613  82175    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4698508 --prefix=/net/ipv4/neigh/veth4698508 --prefix=/net/ipv6/conf/veth4698508 --prefix=/net/ipv6/neigh/veth4698508\n16.102  cat              82616  82615    0 /usr/bin/cat executable\n16.104  cat              82617  82615    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:34:45.534888-73924/uid\n16.106  journalctl       82618  82615    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n16.108  containerd-shim  82619  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6ee5aa6 start\n16.111  containerd-shim  82626  82619    0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6ee5aa6 -address /var/run/docker/containerd/containerd.sock\n16.114  runc             82635  82626    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6e f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6ee5aa6\n16.119  abrt-action-cor  82641  82459    0 /usr/libexec/abrt-action-coredump -r\n16.120  exe              82643  82635    0 /proc/self/exe init\n16.153  exe              82653  82635    0 /proc/1599/exe -exec-root=/var/run/docker f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6ee5aa6 d7da31e8f8e1\n16.169  abrt-handle-eve  82660  82304    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.173  exe              82662  1599     0 /proc/self/exe /var/run/docker/netns/7722c4bb484e all false\n16.182  sh               82671  82660    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n16.183  dbus-send        82671  82660    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.186  sh               82674  82660    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n16.187  abrt-action-not  82675  82674    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.225  runc             82681  82626    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6e --log-format json --systemd-cgroup start f30c4ea62439731e8f4e7b6f451e257a025311bea02b5dcac3e37065d6ee5aa6\n16.230  sh               82647  82626    0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.231  cargo            82687  82647    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n16.242  cargo-native-tr  82687  82647    0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n16.243  16               82691  1        0 /proc/self/fd/16 --deserialize 137 --log-level info --log-target journal-or-kmsg\n16.247  cargo            82692  82687    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.256  abrt-dbus        82691  1        0 /usr/sbin/abrt-dbus -t133\n16.259  rustc            82693  82692    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.270  rustc            82695  82692    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.284  sh               82703  82675    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n16.285  reporter-system  82703  82675    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n16.288  execsnoop        82704  82687    0 /usr/local/bin/execsnoop -t\n16.289  python3          82704  82687    0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.176  git              82710  2235138   0 /usr/bin/git config --get commit.template\n17.192  git              82711  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n17.210  git              82712  2235138   0 /usr/bin/git status -z -uall\n17.227  git              82713  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n17.466  runc             82714  3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process3716857347 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n17.471  exe              82722  82714    0 /proc/self/exe init\n17.492  etcdctl          82724  82714    0 /usr/local/bin/etcdctl endpoint health\n17.669  git              82739  2235138   0 /usr/bin/git worktree list --porcelain\n17.823  cargo            82740  82450    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.837  rustc            82741  82740    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.856  rustc            82747  82740    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n17.949  sh               82751  2147557   0 /bin/sh -c which ps\n17.951  which            82751  2147557   0 /usr/bin/which ps\n17.953  sh               82752  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.955  ps               82752  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.986  sh               82753  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.987  cpuUsage.sh      82753  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.989  sed              82754  82753    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.991  cat              82755  82753    0 /usr/bin/cat /proc/2240539/stat\n17.993  cat              82756  82753    0 /usr/bin/cat /proc/4193716/stat\n17.994  sleep            82757  82753    0 /usr/bin/sleep 1\n18.024  cargo            82758  82325    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.037  rustc            82759  82758    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.057  rustc            82775  82758    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.058  rustc            82777  82758    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0b3033f3338346bd ...\n18.058  rustc            82776  82758    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name core_foundation_sys --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/core-foundation-sys-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"link\" --check-cfg cfg(docsrs,test) ...\n18.124  cc               82868  82747    0 /tmp/native-trace-82450-1783992885668/shims/cc -m64 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/rustcZwBNCf/symbols.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.03ed02i528934v0hmjzocfwy6.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.07qzmpbdqvjqtgmk5iovi03ou.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0a1j7385zj1dnhdx7mgyaeio9.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0c1fv380bielmakxlryin6ddh.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0irnafe09lfeepm33cjnk80z7.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0q8txkg232l1ajzji3wkdgb8e.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0zavkj1xbxp9olmdycqikzrir.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.16hi055u99lagkwidvsdzc2sz.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.18b7gboh39s3ctndr53z6aalf.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1p3fgzo92ubc6cnk1n5tkgwjg.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1sb4yftkyxs9zho1hsrjatb05.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.20eryb3ybfvz4hg0psuxgkf5u.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.25ywm0zgjx7xfg3rezsq6nln4.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.29mnwj50d939ns67hhgpyrv5k.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2e1ckot5ze1ifqjv1w5websvh.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fd1wt3koiv5gt7i5yip4o1d2.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fn9c1cehny0t2a52g5zem5xs.1k2zhvw.rcgu.o ...\n18.127  cc               82882  82868    0 /usr/bin/cc -m64 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/rustcZwBNCf/symbols.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.03ed02i528934v0hmjzocfwy6.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.07qzmpbdqvjqtgmk5iovi03ou.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0a1j7385zj1dnhdx7mgyaeio9.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0c1fv380bielmakxlryin6ddh.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0irnafe09lfeepm33cjnk80z7.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0q8txkg232l1ajzji3wkdgb8e.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0zavkj1xbxp9olmdycqikzrir.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.16hi055u99lagkwidvsdzc2sz.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.18b7gboh39s3ctndr53z6aalf.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1p3fgzo92ubc6cnk1n5tkgwjg.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1sb4yftkyxs9zho1hsrjatb05.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.20eryb3ybfvz4hg0psuxgkf5u.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.25ywm0zgjx7xfg3rezsq6nln4.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.29mnwj50d939ns67hhgpyrv5k.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2e1ckot5ze1ifqjv1w5websvh.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fd1wt3koiv5gt7i5yip4o1d2.1k2zhvw.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fn9c1cehny0t2a52g5zem5xs.1k2zhvw.rcgu.o ...\n18.132  collect2         82892  82882    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc36jZUl.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.134  cross            82895  4193716   0 /home/xmoe/.local/bin/cross build --target powerpc64le-unknown-linux-gnu\n18.136  ld.lld           82901  82892    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc36jZUl.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87 ...\n18.138  rust-lld         82901  82892    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc36jZUl.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.138  rustc            82899  82895    0 /home/xmoe/.cargo/bin/rustc --print target-list\n18.144  rustc            82899  82895    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n18.148  cc               82913  82777    0 /tmp/native-trace-82325-1783992885567/shims/cc -m64 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/rustckoJguu/symbols.o /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.08xsa41xf04swsmxtcva73iaz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.0h37aofhusrl4ripqg5df6866.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.0hqnjb2lez043n75qc4hkofgz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1b69m4dtr7j1wasbmbsnybw4v.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1ej7r5av2lea3vkph6f110nrk.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1t53yq88i9ftx6feewl08g0dz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1zbka6gqhcyemmty761qxtym3.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.2ftt27iiruuk7o5k3dt3cbt3j.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.2tbyiomy52jcb282p4oe5zp5g.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.3nby01yamainihvmyj0ioqpkw.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.4n7inizkjgf7pljvn13ubv7pz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.4oc1flbmcwlkpvd79362sfc9b.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.525gzycdwgigqmfme4nu54l22.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.52fram4mu3meh083fc317sfld.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.5pv5utk8xw6gxmbckwpji5hva.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.63f2ls55pdw6ah7kmlysq29zx.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.6pebuju04o30e6qjf9fcbkc9q.0w05 ...\n18.150  cc               82914  82913    0 /usr/bin/cc -m64 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/rustckoJguu/symbols.o /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.08xsa41xf04swsmxtcva73iaz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.0h37aofhusrl4ripqg5df6866.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.0hqnjb2lez043n75qc4hkofgz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1b69m4dtr7j1wasbmbsnybw4v.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1ej7r5av2lea3vkph6f110nrk.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1t53yq88i9ftx6feewl08g0dz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.1zbka6gqhcyemmty761qxtym3.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.2ftt27iiruuk7o5k3dt3cbt3j.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.2tbyiomy52jcb282p4oe5zp5g.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.3nby01yamainihvmyj0ioqpkw.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.4n7inizkjgf7pljvn13ubv7pz.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.4oc1flbmcwlkpvd79362sfc9b.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.525gzycdwgigqmfme4nu54l22.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.52fram4mu3meh083fc317sfld.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.5pv5utk8xw6gxmbckwpji5hva.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.63f2ls55pdw6ah7kmlysq29zx.0w05 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22.6pebuju04o30e6qjf9fcbkc9q.0w05 ...\n18.154  collect2         82931  82914    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Sx94R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.156  ld.lld           82933  82931    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Sx94R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build_script_build-86fa9ce7c10c4c22 ...\n18.159  rust-lld         82933  82931    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Sx94R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.163  rustc            82937  82895    0 /home/xmoe/.cargo/bin/rustc -vV\n18.170  rustc            82937  82895    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.186  cargo            82964  82895    0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n18.193  cargo            82964  82895    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n18.209  rustc            82977  82964    0 \n18.221  rustc            82980  82964    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.233  build-script-bu  82985  82758    0 /target/debug/build/system-configuration-sys-86fa9ce7c10c4c22/build-script-build\n18.236  rustc            82986  82964    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.239  build-script-bu  82989  82740    0 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build-script-build\n18.240  cc               82987  82775    0 /tmp/native-trace-82325-1783992885567/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcafM8VX/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.241  cc               82990  82987    0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcafM8VX/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.243  rustc            82991  82989    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.246  collect2         82992  82990    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb7csLU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.247  ld.lld           82996  82992    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb7csLU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n18.249  rust-lld         82996  82992    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb7csLU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.257  cargo            83001  82464    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.260  rustc            83000  82740    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n"
    },
    {
      "argv": [
        "/target/debug/build/unicase-846ae3192758395d/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 78065,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/unicase-846ae3192758395d/build-script-build",
      "pid": 78065,
      "ppid": 77319,
      "root_cargo_pid": 77319,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 78065,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 78066,
      "ppid": 78065,
      "root_cargo_pid": 77319,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 78065,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 78076,
      "ppid": 78065,
      "root_cargo_pid": 77319,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 78065,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 78115,
      "ppid": 78065,
      "root_cargo_pid": 77319,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 78065,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 78144,
      "ppid": 78065,
      "root_cargo_pid": 77319,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "unicase",
      "cwd": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "event_id": "bsrun:f939409873bf8eac:f45bd61f2d409c5e:13a358b6d37bd762",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/unicase-846ae3192758395d/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
      "out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
      "success": true,
      "target": null,
      "version": "2.6.0",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-4hhhdpjw/src/unicase-2.6.0",
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
      "build_script_root_pid": 78065,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 78066,
      "ppid": 78065,
      "root_cargo_pid": 77319,
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
      "build_script_root_pid": 78065,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 78076,
      "ppid": 78065,
      "root_cargo_pid": 77319,
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
      "build_script_root_pid": 78065,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 78115,
      "ppid": 78065,
      "root_cargo_pid": 77319,
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
      "build_script_root_pid": 78065,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 78144,
      "ppid": 78065,
      "root_cargo_pid": 77319,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 454,
    "crate": "unicase",
    "version": "2.6.0",
    "crate_id": "749",
    "version_id": "189280",
    "downloads": 70699681,
    "cumulative_downloads": 68019855234,
    "cumulative_share_of_global": 0.25431053594079817,
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
