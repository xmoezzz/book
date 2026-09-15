# `unicase` `2.6.0`

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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G",
    "/target/debug/build/unicase-846ae3192758395d",
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
      "directory": "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-75604-1783992866584431636.map",
  "pid": 75604,
  "ppid": 75586,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-75604-1783992866584431636.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "workspace_root": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
      "name": "unicase",
      "version": "2.6.0",
      "manifest_path": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0"
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
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 75604,
  "ppid": 75586,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "event_id": "used:cc:3334d2cb7b714af6:510f7e4989a54571:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
  "pid": 75604,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "event_id": "used:cc:3334d2cb7b714af6:4aba49403ea985a2:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
  "pid": 75604,
  "sha256": "9210c49b79f0750e786c4cf0da2b738ebff2c5e6908bf54d599b46a6040c5d24",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "event_id": "used:cc:3334d2cb7b714af6:e463a64d2bbc9926:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
  "pid": 75604,
  "sha256": "e9ca01afd0a29274ea39a494033fde6a6873c27018c6c10e81ba5c4fa75c3d4b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "event_id": "used:cc:3334d2cb7b714af6:d6cb5f21b9742bfd:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
  "pid": 75604,
  "sha256": "0cd051d16b3b015f51ef531dcb63b09ecd9ed685397505da933696dfd87e20fc",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "event_id": "used:cc:3334d2cb7b714af6:634559ca53dadbf6:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
  "pid": 75604,
  "sha256": "409e6e5b457dca4be405ec444ed686f1ad8bfc1f7e09eaf07300b0e4b34313f6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "event_id": "used:cc:3334d2cb7b714af6:0b927f82217ac183:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
  "pid": 75604,
  "sha256": "87eab9920567f3306e494268efad1658bf3953a3463f07fb96a4981483ce830f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "event_id": "used:cc:3334d2cb7b714af6:fb0fe3552dc1f238:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
  "pid": 75604,
  "sha256": "c0531411772c11da745d21f71c66ce59a272bc96987cf2b887c1301842873b53",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "event_id": "used:cc:3334d2cb7b714af6:3637dc948453dbe5:0829e35ddf33f771",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
  "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
  "pid": 75604,
  "sha256": "91b0ef9692d5720a82899f6f887251aafecf6cc42b3b1d1802ab1ef32be9d37f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "cargo_pkg_name": "unicase",
  "cargo_pkg_version": "2.6.0",
  "context_path": "/tmp/native-trace-75099-1783992864115/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-75099-1783992864115/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 75604,
  "ppid": 75586,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
    "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G",
    "/target/debug/build/unicase-846ae3192758395d",
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
      "directory": "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/unicase-846ae3192758395d",
      "kind": "object",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-75604-1783992866584431636.map",
  "pid": 75604,
  "ppid": 75586,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-75604-1783992866584431636.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
  "parse_error_count": 1,
  "parsed_event_count": 1518,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1519,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": " zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.494  as               81177  81146    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-entropy_common.o /tmp/cchhI3Qi.s\n12.503  riscv64-linux-g  81175  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.504  as               81178  81154    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-pool.o /tmp/ccdBKJb7.s\n12.510  riscv64-linux-g  81179  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.511  cc1              81180  81175    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.515  cc1              81182  81179    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.517  riscv64-linux-g  81181  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.520  powerpc64le-lin  81172  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.523  cc1              81184  81181    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.525  cc1              81186  81172    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.530  powerpc64le-lin  81185  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.533  riscv64-linux-g  81183  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.536  as               81187  81122    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/88f362f13b0528ed-zstd_ddict.o /tmp/cchi1sDf.s\n12.538  as               81191  81150    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-fse_decompress.o /tmp/ccX6h7go.s\n12.541  cc1              81190  81185    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.542  riscv64-linux-g  81189  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.544  cc1              81192  81183    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.548  riscv64-linux-g  81193  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.551  powerpc64le-lin  81188  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.552  cc1              81195  81193    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.555  cc1              81194  81189    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.558  cc1              81197  81188    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.562  riscv64-linux-g  81196  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.566  cc1              81199  81196    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.584  powerpc64le-lin  81200  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.586  riscv64-linux-g  81198  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.587  sed              81201  80828    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n12.590  cat              81203  80828    0 /usr/bin/cat /proc/2240539/stat\n12.592  cc1              81204  81200    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.593  riscv64-linux-g  81202  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.595  cat              81206  80828    0 /usr/bin/cat /proc/4193716/stat\n12.600  cc1              81209  81198    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.608  cc1              81210  81202    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.613  riscv64-linux-g  81208  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.620  cc1              81211  81208    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.626  riscv64-linux-g  81212  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.631  cc1              81213  81212    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.640  as               81214  81164    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-hist.o /tmp/cclG8D7I.s\n12.670  as               81215  81117    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstdmt_compress.o /tmp/ccVScjmS.s\n12.707  as               81216  81083    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_double_fast.o /tmp/ccIpyiDl.s\n12.708  as               81217  81158    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-zstd_common.o /tmp/ccX2SRnJ.s\n12.728  as               81218  81188    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v01.o /tmp/ccfLfmKe.s\n12.732  as               81219  81202    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_preSplit.o /tmp/ccL0eVpa.s\n12.740  riscv64-linux-g  81220  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.749  powerpc64le-lin  81222  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.753  riscv64-linux-g  81223  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.756  as               81224  81072    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-huf_compress.o /tmp/ccC1srvv.s\n12.760  cc1              81226  81222    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.761  cc1              81221  81220    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.768  cc1              81225  81223    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.794  as               81227  81181    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_superblock.o /tmp/ccOGruJ3.s\n12.795  as               81228  81161    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-fse_compress.o /tmp/cc3740R9.s\n12.816  as               81229  81125    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/88f362f13b0528ed-zstd_decompress.o /tmp/ccJlGcIw.s\n12.817  as               81230  81163    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/a6c81c75fc82913a-divsufsort.o /tmp/cc72IjRl.s\n12.838  as               81231  81196    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_ldm.o /tmp/ccyThKOW.s\n12.852  as               81232  81172    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/a6c81c75fc82913a-fastcover.o /tmp/ccy82343.s\n12.858  as               81233  81160    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/a6c81c75fc82913a-cover.o /tmp/ccRFsko9.s\n12.872  powerpc64le-lin  81235  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.877  riscv64-linux-g  81234  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.882  cc1              81237  81235    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.883  as               81239  81175    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_literals.o /tmp/ccQhhMYP.s\n12.885  cc1              81240  81234    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.887  riscv64-linux-g  81238  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.890  powerpc64le-lin  81236  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.896  cc1              81244  81238    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.897  cc1              81243  81236    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.900  powerpc64le-lin  81242  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.905  riscv64-linux-g  81241  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.910  cc1              81247  81242    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.911  cc1              81248  81241    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.915  powerpc64le-lin  81245  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.915  riscv64-linux-g  81246  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.918  cc1              81249  81246    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.922  cc1              81251  81245    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.928  powerpc64le-lin  81250  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.934  cc1              81252  81250    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -lang-asm -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.967  as               81254  81220    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/88f362f13b0528ed-zstd_ddict.o /tmp/cc1XVoYI.s\n12.968  as               81255  81085    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_fast.o /tmp/cctHW34r.s\n12.989  as               81256  81200    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v02.o /tmp/ccnZ2eV9.s\n13.011  as               81257  81179    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_sequences.o /tmp/ccDdF8Ad.s\n13.047  riscv64-linux-g  81258  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.054  as               81261  81168    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-huf_compress.o /tmp/ccz0GkFW.s\n13.056  as               81260  81185    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/a6c81c75fc82913a-zdict.o /tmp/cclA5Aw2.s\n13.057  cc1              81262  81258    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.060  riscv64-linux-g  81259  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.069  riscv64-linux-g  81263  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.072  cc1              81264  81259    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.077  as               81253  81250    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as --gdwarf2 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/7faed3f8272f2313-huf_decompress_amd64.o /tmp/ccl98KNW.s\n13.124  cc1              81265  81263    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.145  as               81266  81222    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v03.o /tmp/ccSrrj0N.s\n13.151  as               81267  81235    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v04.o /tmp/ccsKkc0M.s\n13.157  as               81268  81236    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v05.o /tmp/ccITelqR.s\n13.190  as               81269  81238    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/a6c81c75fc82913a-cover.o /tmp/cchyeJYl.s\n13.194  as               81271  81134    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/88f362f13b0528ed-zstd_decompress_block.o /tmp/cckveqTc.s\n13.201  riscv64-linux-g  81270  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.205  cc1              81272  81270    0 \n13.220  as               81273  81119    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/88f362f13b0528ed-huf_decompress.o /tmp/ccNh7eW3.s\n13.250  as               81274  81208    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstdmt_compress.o /tmp/cctIvBRi.s\n13.258  as               81275  81259    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v01.o /tmp/ccC4Zqm6.s\n13.261  as               81276  81246    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/a6c81c75fc82913a-fastcover.o /tmp/ccOqVnDw.s\n13.285  as               81277  81110    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_opt.o /tmp/cc6G8eYk.s\n13.312  as               81278  81212    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/88f362f13b0528ed-huf_decompress.o /tmp/cc3IiO0O.s\n13.324  as               81281  81241    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/a6c81c75fc82913a-divsufsort.o /tmp/ccPXXRAh.s\n13.325  riscv64-linux-g  81279  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.325  as               81280  81183    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_double_fast.o /tmp/ccR8MOyV.s\n13.333  cc1              81283  81279    0 \n13.334  riscv64-linux-g  81282  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.337  cc1              81285  81282    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.344  riscv64-linux-g  81284  81024    0 \n13.351  cc1              81286  81284    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.366  as               81288  81189    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_fast.o /tmp/cc3CBk9e.s\n13.370  riscv64-linux-g  81287  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.378  cc1              81290  81287    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.382  as               81291  81242    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v06.o /tmp/cch4pPoj.s\n13.388  riscv64-linux-g  81289  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.393  as               81292  81223    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/88f362f13b0528ed-zstd_decompress.o /tmp/ccTPsSTx.s\n13.394  cc1              81293  81289    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -lang-asm -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= ...\n13.399  as               81294  81263    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v02.o /tmp/ccT2D2Py.s\n13.400  as               81295  81075    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_compress.o /tmp/ccgWPKCI.s\n13.414  as               81296  81289    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/7faed3f8272f2313-huf_decompress_amd64.o /tmp/ccx2H1oD.s\n13.426  as               81297  81245    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v07.o /tmp/ccs3Ymoy.s\n13.448  as               81298  81234    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/88f362f13b0528ed-zstd_decompress_block.o /tmp/ccMbzlNL.s\n13.454  as               81299  81258    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/a6c81c75fc82913a-zdict.o /tmp/ccGx4404.s\n13.463  as               81300  81270    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v03.o /tmp/ccoLP1v2.s\n13.479  cargo            81301  80452    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n13.497  rustc            81302  81301    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n13.522  rustc            81308  81301    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n13.527  as               81309  81173    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress.o /tmp/ccM3qnNQ.s\n13.540  as               81313  81198    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_opt.o /tmp/ccGUdWPL.s\n13.556  as               81314  81282    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v05.o /tmp/cc08BxhC.s\n13.560  as               81316  81279    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v04.o /tmp/ccIHJGq3.s\n13.564  as               81315  81284    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v06.o /tmp/ccWGhZJG.s\n13.610  as               81317  81287    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v07.o /tmp/ccXU5017.s\n13.765  cc               81394  81308    0 /tmp/native-trace-80452-1783992876516/shims/cc -m64 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/rustcXnqePg/symbols.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.03ed02i528934v0hmjzocfwy6.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.07qzmpbdqvjqtgmk5iovi03ou.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0a1j7385zj1dnhdx7mgyaeio9.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0c1fv380bielmakxlryin6ddh.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0irnafe09lfeepm33cjnk80z7.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0q8txkg232l1ajzji3wkdgb8e.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0zavkj1xbxp9olmdycqikzrir.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.16hi055u99lagkwidvsdzc2sz.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.18b7gboh39s3ctndr53z6aalf.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1p3fgzo92ubc6cnk1n5tkgwjg.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1sb4yftkyxs9zho1hsrjatb05.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.20eryb3ybfvz4hg0psuxgkf5u.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.25ywm0zgjx7xfg3rezsq6nln4.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.29mnwj50d939ns67hhgpyrv5k.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2e1ckot5ze1ifqjv1w5websvh.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fd1wt3koiv5gt7i5yip4o1d2.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fn9c1cehny0t2a52g5zem5xs.0lo49qq.rcgu.o ...\n13.766  cc               81395  81394    0 /usr/bin/cc -m64 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/rustcXnqePg/symbols.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.03ed02i528934v0hmjzocfwy6.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.07qzmpbdqvjqtgmk5iovi03ou.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0a1j7385zj1dnhdx7mgyaeio9.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0c1fv380bielmakxlryin6ddh.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0irnafe09lfeepm33cjnk80z7.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0q8txkg232l1ajzji3wkdgb8e.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0zavkj1xbxp9olmdycqikzrir.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.16hi055u99lagkwidvsdzc2sz.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.18b7gboh39s3ctndr53z6aalf.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1p3fgzo92ubc6cnk1n5tkgwjg.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1sb4yftkyxs9zho1hsrjatb05.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.20eryb3ybfvz4hg0psuxgkf5u.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.25ywm0zgjx7xfg3rezsq6nln4.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.29mnwj50d939ns67hhgpyrv5k.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2e1ckot5ze1ifqjv1w5websvh.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fd1wt3koiv5gt7i5yip4o1d2.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fn9c1cehny0t2a52g5zem5xs.0lo49qq.rcgu.o ...\n13.771  collect2         81396  81395    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccumuktW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.773  ld.lld           81397  81396    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccumuktW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87 ...\n13.774  rust-lld         81397  81396    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccumuktW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.841  build-script-bu  81415  81301    0 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build-script-build\n13.843  rustc            81416  81415    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n13.858  rustc            81419  81301    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n14.305  as               81481  81193    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_lazy.o /tmp/ccCQ28gp.s\n14.377  as               81482  81087    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_lazy.o /tmp/ccxhYBrB.s\n14.469  runc             81483  69707    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71e --log-format json --systemd-cgroup kill --all 0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71ecf194 9\n14.487  runc             81489  69707    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71e --log-format json --systemd-cgroup delete 0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71ecf194\n14.549  powerpc64le-lin  81495  80935    0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/libzstd.a /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-debug.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-entropy_common.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-error_private.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-fse_decompress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-pool.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-threading.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-zstd_common.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-fse_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-hist.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-huf_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_compress_literals.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_compress_sequences.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_compress_superblock.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_double_fast.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_fast.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_lazy.o ...\n14.564  powerpc64le-lin  81496  80935    0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/libzstd.a\n14.578  build-script-bu  81499  79802    0 /target/debug/build/zstd-safe-ba4648616b716f35/build-script-build\n14.582  rustc            81500  79802    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_sys --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zstd-sys-2.0.15+zstd.1.5.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"legacy\" --cfg feature=\"zdict_builder\" --check-cfg ...\n14.617  rustc            81508  79802    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_safe --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"arrays\" --cfg feature=\"default\" --cfg ...\n14.667  containerd-shim  81512  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71ecf194 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71e delete\n14.669  runc             81520  81512    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71ecf19 --log-format json delete --force 0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71ecf194\n14.705  sh               81546  81543    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vetha54e8bd\n14.706  ethtool          81547  81546    0 /usr/sbin/ethtool -i vetha54e8bd\n14.706  sed              81548  81546    0 /usr/bin/sed -n s/^driver: //p\n14.709  riscv64-linux-g  81550  81024    0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/libzstd.a /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-debug.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-entropy_common.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-error_private.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-fse_decompress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-pool.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-threading.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-zstd_common.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-fse_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-hist.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-huf_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_literals.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_sequences.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_superblock.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_double_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_lazy.o ...\n14.712  systemd-sysctl   81552  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha54e8bd --prefix=/net/ipv4/neigh/vetha54e8bd --prefix=/net/ipv6/conf/vetha54e8bd --prefix=/net/ipv6/neigh/vetha54e8bd\n14.775  riscv64-linux-g  81554  81024    0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/libzstd.a\n14.838  build-script-bu  81557  79910    0 /target/debug/build/zstd-safe-ba4648616b716f35/build-script-build\n14.842  rustc            81558  79910    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_sys --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zstd-sys-2.0.15+zstd.1.5.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"legacy\" --cfg feature=\"zdict_builder\" --check-cfg ...\n14.879  rustc            81566  79910    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_safe --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"arrays\" --cfg feature=\"default\" --cfg ...\n15.159  runc             81586  74391    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 --log-format json --systemd-cgroup kill --all f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e 9\n15.177  runc             81592  74391    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 --log-format json --systemd-cgroup delete f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e\n15.356  containerd-shim  81598  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 delete\n15.359  runc             81605  81598    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6 --log-format json delete --force f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e\n15.399  systemd-sysctl   81610  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b6db40 --prefix=/net/ipv4/neigh/veth5b6db40 --prefix=/net/ipv6/conf/veth5b6db40 --prefix=/net/ipv6/neigh/veth5b6db40\n16.521  sh               81612  2147557   0 /bin/sh -c which ps\n16.523  which            81612  2147557   0 /usr/bin/which ps\n16.526  sh               81613  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.527  ps               81613  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.555  runc             81614  70730    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 --log-format json --systemd-cgroup kill --all 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966 9\n16.558  sh               81620  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.560  cpuUsage.sh      81620  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.562  sed              81621  81620    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.565  cat              81622  81620    0 /usr/bin/cat /proc/2240539/stat\n16.565  runc             81623  70730    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 --log-format json --systemd-cgroup delete 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966\n16.566  cat              81624  81620    0 /usr/bin/cat /proc/4193716/stat\n16.568  sleep            81630  81620    0 /usr/bin/sleep 1\n16.773  containerd-shim  81632  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 delete\n16.776  runc             81639  81632    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef96 --log-format json delete --force 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966\n16.803  runc             81644  70770    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a --log-format json --systemd-cgroup kill --all 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b 9\n16.813  runc             81650  70770    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a --log-format json --systemd-cgroup delete 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b\n16.817  systemd-sysctl   81656  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf8b421b --prefix=/net/ipv4/neigh/vethf8b421b --prefix=/net/ipv6/conf/vethf8b421b --prefix=/net/ipv6/neigh/vethf8b421b\n17.020  containerd-shim  81657  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a delete\n17.023  runc             81664  81657    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901 --log-format json delete --force 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b\n17.062  systemd-sysctl   81669  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth77ef5ac --prefix=/net/ipv4/neigh/veth77ef5ac --prefix=/net/ipv6/conf/veth77ef5ac --prefix=/net/ipv6/neigh/veth77ef5ac\n"
}
```

#### Record 16

```json
{
  "argv": [
    "/target/debug/build/unicase-846ae3192758395d/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 75631,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/unicase-846ae3192758395d/build-script-build",
  "pid": 75631,
  "ppid": 75554,
  "root_cargo_pid": 75554,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
  "build_script_root_pid": 75631,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 75632,
  "ppid": 75631,
  "root_cargo_pid": 75554,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "_build_script_out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
  "build_script_root_pid": 75631,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 75634,
  "ppid": 75631,
  "root_cargo_pid": 75554,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "_build_script_out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
  "build_script_root_pid": 75631,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 75636,
  "ppid": 75631,
  "root_cargo_pid": 75554,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "_build_script_out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
  "build_script_root_pid": 75631,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 75638,
  "ppid": 75631,
  "root_cargo_pid": 75554,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "_build_script_out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 21

```json
{
  "crate": "unicase",
  "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "event_id": "bsrun:8df881ab64113b9b:f45bd61f2d409c5e:13a358b6d37bd762",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/unicase-846ae3192758395d/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
  "out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
  "success": true,
  "target": null,
  "version": "2.6.0",
  "_owner": {
    "crate": "unicase",
    "version": "2.6.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
    "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
  "build_script_root_pid": 75631,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 75632,
  "ppid": 75631,
  "root_cargo_pid": 75554,
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
  "build_script_root_pid": 75631,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 75634,
  "ppid": 75631,
  "root_cargo_pid": 75554,
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
  "build_script_root_pid": 75631,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 75636,
  "ppid": 75631,
  "root_cargo_pid": 75554,
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
  "build_script_root_pid": 75631,
  "build_script_target_dir": "unicase-846ae3192758395d",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 75638,
  "ppid": 75631,
  "root_cargo_pid": 75554,
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
  "time": "2026-07-14T01:34:44.177625+00:00",
  "crate": "unicase",
  "version": "2.6.0",
  "architecture": "riscv64",
  "duration_seconds": 24.09984437888488,
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
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "manifest_path": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "workspace_root": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
          "name": "unicase",
          "version": "2.6.0",
          "manifest_path": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0"
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
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 75604,
      "ppid": 75586,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "event_id": "used:cc:3334d2cb7b714af6:510f7e4989a54571:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
      "pid": 75604,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "event_id": "used:cc:3334d2cb7b714af6:4aba49403ea985a2:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
      "pid": 75604,
      "sha256": "9210c49b79f0750e786c4cf0da2b738ebff2c5e6908bf54d599b46a6040c5d24",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "event_id": "used:cc:3334d2cb7b714af6:e463a64d2bbc9926:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
      "pid": 75604,
      "sha256": "e9ca01afd0a29274ea39a494033fde6a6873c27018c6c10e81ba5c4fa75c3d4b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "event_id": "used:cc:3334d2cb7b714af6:d6cb5f21b9742bfd:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
      "pid": 75604,
      "sha256": "0cd051d16b3b015f51ef531dcb63b09ecd9ed685397505da933696dfd87e20fc",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "event_id": "used:cc:3334d2cb7b714af6:634559ca53dadbf6:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
      "pid": 75604,
      "sha256": "409e6e5b457dca4be405ec444ed686f1ad8bfc1f7e09eaf07300b0e4b34313f6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "event_id": "used:cc:3334d2cb7b714af6:0b927f82217ac183:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
      "pid": 75604,
      "sha256": "87eab9920567f3306e494268efad1658bf3953a3463f07fb96a4981483ce830f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "event_id": "used:cc:3334d2cb7b714af6:fb0fe3552dc1f238:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
      "pid": 75604,
      "sha256": "c0531411772c11da745d21f71c66ce59a272bc96987cf2b887c1301842873b53",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "event_id": "used:cc:3334d2cb7b714af6:3637dc948453dbe5:0829e35ddf33f771",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d",
      "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
      "pid": 75604,
      "sha256": "91b0ef9692d5720a82899f6f887251aafecf6cc42b3b1d1802ab1ef32be9d37f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "cargo_pkg_name": "unicase",
      "cargo_pkg_version": "2.6.0",
      "context_path": "/tmp/native-trace-75099-1783992864115/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-75099-1783992864115/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 75604,
      "ppid": 75586,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
        "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G",
        "/target/debug/build/unicase-846ae3192758395d",
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
          "directory": "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/rustcQfkJ2G/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.2lni4rev7lvmi1zrqrpu5sp38.0127g8l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.3sy4rme5y60qma1rysjp9zpts.0127g8l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.awdjmlx0zdft41ized6dp28t0.0127g8l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.dir32nw0ksy4zs7ntx14lckpt.0127g8l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.em8oznw3aal2vttr1cm0d5f91.0127g8l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.enloi3y48k78xm0orcnqwhaoh.0127g8l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/unicase-846ae3192758395d",
          "kind": "object",
          "path": "/target/debug/build/unicase-846ae3192758395d/build_script_build-846ae3192758395d.9te4g5xsk6orz2ikq8o5qwz59.0127g8l.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-75604-1783992866584431636.map",
      "pid": 75604,
      "ppid": 75586,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-75604-1783992866584431636.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
      "parsed_event_count": 1518,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1519,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": " zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.494  as               81177  81146    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-entropy_common.o /tmp/cchhI3Qi.s\n12.503  riscv64-linux-g  81175  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.504  as               81178  81154    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-pool.o /tmp/ccdBKJb7.s\n12.510  riscv64-linux-g  81179  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.511  cc1              81180  81175    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.515  cc1              81182  81179    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.517  riscv64-linux-g  81181  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.520  powerpc64le-lin  81172  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.523  cc1              81184  81181    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.525  cc1              81186  81172    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.530  powerpc64le-lin  81185  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.533  riscv64-linux-g  81183  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.536  as               81187  81122    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/88f362f13b0528ed-zstd_ddict.o /tmp/cchi1sDf.s\n12.538  as               81191  81150    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-fse_decompress.o /tmp/ccX6h7go.s\n12.541  cc1              81190  81185    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.542  riscv64-linux-g  81189  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.544  cc1              81192  81183    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.548  riscv64-linux-g  81193  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.551  powerpc64le-lin  81188  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.552  cc1              81195  81193    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.555  cc1              81194  81189    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.558  cc1              81197  81188    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.562  riscv64-linux-g  81196  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.566  cc1              81199  81196    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.584  powerpc64le-lin  81200  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.586  riscv64-linux-g  81198  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.587  sed              81201  80828    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n12.590  cat              81203  80828    0 /usr/bin/cat /proc/2240539/stat\n12.592  cc1              81204  81200    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.593  riscv64-linux-g  81202  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.595  cat              81206  80828    0 /usr/bin/cat /proc/4193716/stat\n12.600  cc1              81209  81198    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.608  cc1              81210  81202    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.613  riscv64-linux-g  81208  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.620  cc1              81211  81208    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.626  riscv64-linux-g  81212  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.631  cc1              81213  81212    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.640  as               81214  81164    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-hist.o /tmp/cclG8D7I.s\n12.670  as               81215  81117    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstdmt_compress.o /tmp/ccVScjmS.s\n12.707  as               81216  81083    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_double_fast.o /tmp/ccIpyiDl.s\n12.708  as               81217  81158    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-zstd_common.o /tmp/ccX2SRnJ.s\n12.728  as               81218  81188    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v01.o /tmp/ccfLfmKe.s\n12.732  as               81219  81202    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_preSplit.o /tmp/ccL0eVpa.s\n12.740  riscv64-linux-g  81220  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.749  powerpc64le-lin  81222  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.753  riscv64-linux-g  81223  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.756  as               81224  81072    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-huf_compress.o /tmp/ccC1srvv.s\n12.760  cc1              81226  81222    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.761  cc1              81221  81220    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.768  cc1              81225  81223    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.794  as               81227  81181    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_superblock.o /tmp/ccOGruJ3.s\n12.795  as               81228  81161    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-fse_compress.o /tmp/cc3740R9.s\n12.816  as               81229  81125    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/88f362f13b0528ed-zstd_decompress.o /tmp/ccJlGcIw.s\n12.817  as               81230  81163    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/a6c81c75fc82913a-divsufsort.o /tmp/cc72IjRl.s\n12.838  as               81231  81196    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_ldm.o /tmp/ccyThKOW.s\n12.852  as               81232  81172    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/a6c81c75fc82913a-fastcover.o /tmp/ccy82343.s\n12.858  as               81233  81160    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/a6c81c75fc82913a-cover.o /tmp/ccRFsko9.s\n12.872  powerpc64le-lin  81235  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.877  riscv64-linux-g  81234  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.882  cc1              81237  81235    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.883  as               81239  81175    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_literals.o /tmp/ccQhhMYP.s\n12.885  cc1              81240  81234    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.887  riscv64-linux-g  81238  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.890  powerpc64le-lin  81236  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.896  cc1              81244  81238    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.897  cc1              81243  81236    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.900  powerpc64le-lin  81242  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.905  riscv64-linux-g  81241  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.910  cc1              81247  81242    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.911  cc1              81248  81241    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.915  powerpc64le-lin  81245  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.915  riscv64-linux-g  81246  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n12.918  cc1              81249  81246    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.922  cc1              81251  81245    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= -D ZSTDERRORLIB_VISIBILITY= ...\n12.928  powerpc64le-lin  81250  80935    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 -DXXH_PRIVATE_API= ...\n12.934  cc1              81252  81250    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -lang-asm -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultiarch powerpc64le-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n12.967  as               81254  81220    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/88f362f13b0528ed-zstd_ddict.o /tmp/cc1XVoYI.s\n12.968  as               81255  81085    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_fast.o /tmp/cctHW34r.s\n12.989  as               81256  81200    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v02.o /tmp/ccnZ2eV9.s\n13.011  as               81257  81179    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_sequences.o /tmp/ccDdF8Ad.s\n13.047  riscv64-linux-g  81258  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.054  as               81261  81168    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-huf_compress.o /tmp/ccz0GkFW.s\n13.056  as               81260  81185    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/a6c81c75fc82913a-zdict.o /tmp/cclA5Aw2.s\n13.057  cc1              81262  81258    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.060  riscv64-linux-g  81259  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.069  riscv64-linux-g  81263  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.072  cc1              81264  81259    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.077  as               81253  81250    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as --gdwarf2 -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/7faed3f8272f2313-huf_decompress_amd64.o /tmp/ccl98KNW.s\n13.124  cc1              81265  81263    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.145  as               81266  81222    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v03.o /tmp/ccSrrj0N.s\n13.151  as               81267  81235    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v04.o /tmp/ccsKkc0M.s\n13.157  as               81268  81236    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v05.o /tmp/ccITelqR.s\n13.190  as               81269  81238    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/a6c81c75fc82913a-cover.o /tmp/cchyeJYl.s\n13.194  as               81271  81134    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/88f362f13b0528ed-zstd_decompress_block.o /tmp/cckveqTc.s\n13.201  riscv64-linux-g  81270  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.205  cc1              81272  81270    0 \n13.220  as               81273  81119    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/88f362f13b0528ed-huf_decompress.o /tmp/ccNh7eW3.s\n13.250  as               81274  81208    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstdmt_compress.o /tmp/cctIvBRi.s\n13.258  as               81275  81259    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v01.o /tmp/ccC4Zqm6.s\n13.261  as               81276  81246    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/a6c81c75fc82913a-fastcover.o /tmp/ccOqVnDw.s\n13.285  as               81277  81110    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_opt.o /tmp/cc6G8eYk.s\n13.312  as               81278  81212    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/88f362f13b0528ed-huf_decompress.o /tmp/cc3IiO0O.s\n13.324  as               81281  81241    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/a6c81c75fc82913a-divsufsort.o /tmp/ccPXXRAh.s\n13.325  riscv64-linux-g  81279  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.325  as               81280  81183    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_double_fast.o /tmp/ccR8MOyV.s\n13.333  cc1              81283  81279    0 \n13.334  riscv64-linux-g  81282  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.337  cc1              81285  81282    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.344  riscv64-linux-g  81284  81024    0 \n13.351  cc1              81286  81284    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.366  as               81288  81189    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_fast.o /tmp/cc3CBk9e.s\n13.370  riscv64-linux-g  81287  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.378  cc1              81290  81287    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= -D ZDICTLIB_VISIBILITY= ...\n13.382  as               81291  81242    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v06.o /tmp/cch4pPoj.s\n13.388  riscv64-linux-g  81289  81024    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -fvisibility=hidden -ffunction-sections -fdata-sections -fmerge-all-constants -DZSTD_LIB_DEPRECATED=0 ...\n13.393  as               81292  81223    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/88f362f13b0528ed-zstd_decompress.o /tmp/ccTPsSTx.s\n13.394  cc1              81293  81289    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -lang-asm -quiet -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -imultilib . -imultiarch riscv64-linux-gnu -D ZSTD_LIB_DEPRECATED=0 -D XXH_PRIVATE_API= -D ZSTDLIB_VISIBILITY= ...\n13.399  as               81294  81263    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v02.o /tmp/ccT2D2Py.s\n13.400  as               81295  81075    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_compress.o /tmp/ccgWPKCI.s\n13.414  as               81296  81289    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/7faed3f8272f2313-huf_decompress_amd64.o /tmp/ccx2H1oD.s\n13.426  as               81297  81245    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/3f451b2306bc13c8-zstd_v07.o /tmp/ccs3Ymoy.s\n13.448  as               81298  81234    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/88f362f13b0528ed-zstd_decompress_block.o /tmp/ccMbzlNL.s\n13.454  as               81299  81258    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/a6c81c75fc82913a-zdict.o /tmp/ccGx4404.s\n13.463  as               81300  81270    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v03.o /tmp/ccoLP1v2.s\n13.479  cargo            81301  80452    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n13.497  rustc            81302  81301    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n13.522  rustc            81308  81301    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n13.527  as               81309  81173    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress.o /tmp/ccM3qnNQ.s\n13.540  as               81313  81198    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_opt.o /tmp/ccGUdWPL.s\n13.556  as               81314  81282    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v05.o /tmp/cc08BxhC.s\n13.560  as               81316  81279    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v04.o /tmp/ccIHJGq3.s\n13.564  as               81315  81284    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v06.o /tmp/ccWGhZJG.s\n13.610  as               81317  81287    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/3f451b2306bc13c8-zstd_v07.o /tmp/ccXU5017.s\n13.765  cc               81394  81308    0 /tmp/native-trace-80452-1783992876516/shims/cc -m64 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/rustcXnqePg/symbols.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.03ed02i528934v0hmjzocfwy6.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.07qzmpbdqvjqtgmk5iovi03ou.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0a1j7385zj1dnhdx7mgyaeio9.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0c1fv380bielmakxlryin6ddh.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0irnafe09lfeepm33cjnk80z7.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0q8txkg232l1ajzji3wkdgb8e.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0zavkj1xbxp9olmdycqikzrir.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.16hi055u99lagkwidvsdzc2sz.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.18b7gboh39s3ctndr53z6aalf.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1p3fgzo92ubc6cnk1n5tkgwjg.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1sb4yftkyxs9zho1hsrjatb05.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.20eryb3ybfvz4hg0psuxgkf5u.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.25ywm0zgjx7xfg3rezsq6nln4.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.29mnwj50d939ns67hhgpyrv5k.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2e1ckot5ze1ifqjv1w5websvh.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fd1wt3koiv5gt7i5yip4o1d2.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fn9c1cehny0t2a52g5zem5xs.0lo49qq.rcgu.o ...\n13.766  cc               81395  81394    0 /usr/bin/cc -m64 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/rustcXnqePg/symbols.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.03ed02i528934v0hmjzocfwy6.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.07qzmpbdqvjqtgmk5iovi03ou.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0a1j7385zj1dnhdx7mgyaeio9.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0c1fv380bielmakxlryin6ddh.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0irnafe09lfeepm33cjnk80z7.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0q8txkg232l1ajzji3wkdgb8e.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.0zavkj1xbxp9olmdycqikzrir.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.16hi055u99lagkwidvsdzc2sz.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.18b7gboh39s3ctndr53z6aalf.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1p3fgzo92ubc6cnk1n5tkgwjg.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.1sb4yftkyxs9zho1hsrjatb05.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.20eryb3ybfvz4hg0psuxgkf5u.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.25ywm0zgjx7xfg3rezsq6nln4.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.29mnwj50d939ns67hhgpyrv5k.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2e1ckot5ze1ifqjv1w5websvh.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fd1wt3koiv5gt7i5yip4o1d2.0lo49qq.rcgu.o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87.2fn9c1cehny0t2a52g5zem5xs.0lo49qq.rcgu.o ...\n13.771  collect2         81396  81395    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccumuktW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.773  ld.lld           81397  81396    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccumuktW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build_script_build-5d71fe08e5f8ee87 ...\n13.774  rust-lld         81397  81396    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccumuktW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.841  build-script-bu  81415  81301    0 /target/debug/build/target-lexicon-5d71fe08e5f8ee87/build-script-build\n13.843  rustc            81416  81415    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n13.858  rustc            81419  81301    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n14.305  as               81481  81193    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_lazy.o /tmp/ccCQ28gp.s\n14.377  as               81482  81087    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I zstd/lib/ -I zstd/lib/common -I zstd/lib/legacy -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_lazy.o /tmp/ccxhYBrB.s\n14.469  runc             81483  69707    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71e --log-format json --systemd-cgroup kill --all 0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71ecf194 9\n14.487  runc             81489  69707    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71e --log-format json --systemd-cgroup delete 0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71ecf194\n14.549  powerpc64le-lin  81495  80935    0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/libzstd.a /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-debug.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-entropy_common.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-error_private.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-fse_decompress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-pool.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-threading.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/44ff4c55aa9e5133-zstd_common.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-fse_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-hist.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-huf_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_compress.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_compress_literals.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_compress_sequences.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_compress_superblock.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_double_fast.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_fast.o /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/fb80479a5fb81f6a-zstd_lazy.o ...\n14.564  powerpc64le-lin  81496  80935    0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/zstd-sys-46f77c83a699aa08/out/libzstd.a\n14.578  build-script-bu  81499  79802    0 /target/debug/build/zstd-safe-ba4648616b716f35/build-script-build\n14.582  rustc            81500  79802    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_sys --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zstd-sys-2.0.15+zstd.1.5.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"legacy\" --cfg feature=\"zdict_builder\" --check-cfg ...\n14.617  rustc            81508  79802    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_safe --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"arrays\" --cfg feature=\"default\" --cfg ...\n14.667  containerd-shim  81512  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71ecf194 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71e delete\n14.669  runc             81520  81512    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71ecf19 --log-format json delete --force 0ae61cdf1a31554bafb12aa63292ac2af28617ad74b8137b5cec411e71ecf194\n14.705  sh               81546  81543    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vetha54e8bd\n14.706  ethtool          81547  81546    0 /usr/sbin/ethtool -i vetha54e8bd\n14.706  sed              81548  81546    0 /usr/bin/sed -n s/^driver: //p\n14.709  riscv64-linux-g  81550  81024    0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/libzstd.a /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-debug.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-entropy_common.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-error_private.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-fse_decompress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-pool.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-threading.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/44ff4c55aa9e5133-zstd_common.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-fse_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-hist.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-huf_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_literals.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_sequences.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_compress_superblock.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_double_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_fast.o /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/fb80479a5fb81f6a-zstd_lazy.o ...\n14.712  systemd-sysctl   81552  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha54e8bd --prefix=/net/ipv4/neigh/vetha54e8bd --prefix=/net/ipv6/conf/vetha54e8bd --prefix=/net/ipv6/neigh/vetha54e8bd\n14.775  riscv64-linux-g  81554  81024    0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/zstd-sys-e9e888460794efd4/out/libzstd.a\n14.838  build-script-bu  81557  79910    0 /target/debug/build/zstd-safe-ba4648616b716f35/build-script-build\n14.842  rustc            81558  79910    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_sys --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zstd-sys-2.0.15+zstd.1.5.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"legacy\" --cfg feature=\"zdict_builder\" --check-cfg ...\n14.879  rustc            81566  79910    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zstd_safe --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=non_upper_case_globals --cfg feature=\"arrays\" --cfg feature=\"default\" --cfg ...\n15.159  runc             81586  74391    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 --log-format json --systemd-cgroup kill --all f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e 9\n15.177  runc             81592  74391    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 --log-format json --systemd-cgroup delete f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e\n15.356  containerd-shim  81598  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457 delete\n15.359  runc             81605  81598    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6 --log-format json delete --force f74850821e743feb47c56e66dc401f67c7acdd9b36b9b7f8a945215c457d9d6e\n15.399  systemd-sysctl   81610  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5b6db40 --prefix=/net/ipv4/neigh/veth5b6db40 --prefix=/net/ipv6/conf/veth5b6db40 --prefix=/net/ipv6/neigh/veth5b6db40\n16.521  sh               81612  2147557   0 /bin/sh -c which ps\n16.523  which            81612  2147557   0 /usr/bin/which ps\n16.526  sh               81613  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.527  ps               81613  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.555  runc             81614  70730    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 --log-format json --systemd-cgroup kill --all 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966 9\n16.558  sh               81620  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.560  cpuUsage.sh      81620  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.562  sed              81621  81620    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.565  cat              81622  81620    0 /usr/bin/cat /proc/2240539/stat\n16.565  runc             81623  70730    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 --log-format json --systemd-cgroup delete 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966\n16.566  cat              81624  81620    0 /usr/bin/cat /proc/4193716/stat\n16.568  sleep            81630  81620    0 /usr/bin/sleep 1\n16.773  containerd-shim  81632  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934 delete\n16.776  runc             81639  81632    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef96 --log-format json delete --force 03f6c8a8376c6870d1b8ac547e0b6e2dad940057cdfe922be536ff1a934ef966\n16.803  runc             81644  70770    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a --log-format json --systemd-cgroup kill --all 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b 9\n16.813  runc             81650  70770    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a --log-format json --systemd-cgroup delete 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b\n16.817  systemd-sysctl   81656  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf8b421b --prefix=/net/ipv4/neigh/vethf8b421b --prefix=/net/ipv6/conf/vethf8b421b --prefix=/net/ipv6/neigh/vethf8b421b\n17.020  containerd-shim  81657  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a delete\n17.023  runc             81664  81657    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901 --log-format json delete --force 17247d513d36fa80856a8a6fcefbce0a1663d456d0baa2431179d23e83a1901b\n17.062  systemd-sysctl   81669  81543    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth77ef5ac --prefix=/net/ipv4/neigh/veth77ef5ac --prefix=/net/ipv6/conf/veth77ef5ac --prefix=/net/ipv6/neigh/veth77ef5ac\n"
    },
    {
      "argv": [
        "/target/debug/build/unicase-846ae3192758395d/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 75631,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/unicase-846ae3192758395d/build-script-build",
      "pid": 75631,
      "ppid": 75554,
      "root_cargo_pid": 75554,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 75631,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 75632,
      "ppid": 75631,
      "root_cargo_pid": 75554,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 75631,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 75634,
      "ppid": 75631,
      "root_cargo_pid": 75554,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 75631,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 75636,
      "ppid": 75631,
      "root_cargo_pid": 75554,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 75631,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 75638,
      "ppid": 75631,
      "root_cargo_pid": 75554,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "unicase",
      "cwd": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "event_id": "bsrun:8df881ab64113b9b:f45bd61f2d409c5e:13a358b6d37bd762",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/unicase-846ae3192758395d/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
      "out_dir": "/target/debug/build/unicase-846ae3192758395d/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
      "success": true,
      "target": null,
      "version": "2.6.0",
      "_owner": {
        "crate": "unicase",
        "version": "2.6.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0#unicase@2.6.0",
        "manifest_dir": "/tmp/crate-build-riscv64-08to3l99/src/unicase-2.6.0",
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
      "build_script_root_pid": 75631,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 75632,
      "ppid": 75631,
      "root_cargo_pid": 75554,
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
      "build_script_root_pid": 75631,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 75634,
      "ppid": 75631,
      "root_cargo_pid": 75554,
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
      "build_script_root_pid": 75631,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 75636,
      "ppid": 75631,
      "root_cargo_pid": 75554,
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
      "build_script_root_pid": 75631,
      "build_script_target_dir": "unicase-846ae3192758395d",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 75638,
      "ppid": 75631,
      "root_cargo_pid": 75554,
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
