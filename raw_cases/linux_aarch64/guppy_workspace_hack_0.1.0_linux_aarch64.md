# `guppy-workspace-hack` `0.1.0`

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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
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
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
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
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-380934-1783994292940330549.map",
  "pid": 380934,
  "ppid": 380910,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-380934-1783994292940330549.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "workspace_root": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
      "name": "guppy-workspace-hack",
      "version": "0.1.0",
      "manifest_path": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0"
    }
  ],
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 380934,
  "ppid": 380910,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "guppy-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2fa78141aafe9496:9654dcff812e2b1f:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
  "pid": 380934,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "guppy-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2fa78141aafe9496:a6683e4660d86fd9:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
  "pid": 380934,
  "sha256": "192f6872a48e660566208e186c37ddbd9ceee9b2d0abd7cb17aff178d4ab7631",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "guppy-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2fa78141aafe9496:b27b1f8694553276:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
  "pid": 380934,
  "sha256": "829b295fd101748135b1ef845cc60fbd00f0fc7a043d34b01f259a04a4fdb514",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "guppy-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2fa78141aafe9496:936187359bd39079:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
  "pid": 380934,
  "sha256": "e1eb585ff708f37d45fb26c964a78a02775935df07fe3ae974521079afafc758",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "guppy-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2fa78141aafe9496:11353ab5a8a21cd3:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
  "pid": 380934,
  "sha256": "e93c2416ece7b948a5af9ba7f05292e9b07b604de17b32ecd951dba876e0a0fa",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "guppy-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2fa78141aafe9496:abd889a682f5f794:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
  "pid": 380934,
  "sha256": "5c8119db80fdc3221cdd7b5e95dfe3fe5a57e0bd9d55d52caceec543524a68b6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "guppy-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2fa78141aafe9496:8eb88d76d00ab054:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
  "pid": 380934,
  "sha256": "3886925c78c2d7fa134e01cba1c0a98a1d6e7b338372a370584dc488de578b52",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
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
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "cargo_pkg_name": "guppy-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "context_path": "/tmp/native-trace-380513-1783994290717/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-380513-1783994290717/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 380934,
  "ppid": 380910,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
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
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-380934-1783994292940330549.map",
  "pid": 380934,
  "ppid": 380910,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-380934-1783994292940330549.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
  "parsed_event_count": 1441,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1442,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "p64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.943  cc1              386905 386902   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.947  cc1              386911 386901   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n16.960  aarch64-linux-g  386910 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n16.966  cc1              386912 386906   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.969  rustc            386915 382443   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glib_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glib-macros-0.18.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.979  cc1              386916 386910   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n16.983  riscv64-linux-g  386909 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.987  cc1              386919 386909   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.997  as               386921 386796   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.018  as               386925 386898   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.033  as               386926 386891   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ad45968d24b0237e-base64.o /tmp/cciueJM6.s\n17.033  as               386922 386820   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.039  as               386924 386817   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.067  runc             386929 379546   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b36 --log-format json --systemd-cgroup kill --all 77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b362fde1 9\n17.081  as               386935 386909   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.081  containerd-shim  386936 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201f366d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201 delete\n17.083  as               386937 386787   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.086  runc             386944 386936   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201f366 --log-format json delete --force 2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201f366d\n17.088  riscv64-linux-g  386941 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.092  cross            386951 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n17.093  rustc            386952 386951   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.096  riscv64-linux-g  386946 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.096  runc             386956 379546   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b36 --log-format json --systemd-cgroup delete 77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b362fde1\n17.102  rustc            386952 386951   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.102  cc1              386971 386946   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.116  as               386923 386840   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.117  cc1              386955 386941   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.119  as               386927 386830   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.130  as               386979 386906   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.131  rustc            386980 386951   0 /home/xmoe/.cargo/bin/rustc -vV\n17.137  rustc            386980 386951   0 \n17.137  as               386978 386762   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_type.o /tmp/ccpkob4k.s\n17.137  as               386977 386809   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.140  as               386989 386872   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-tasn_fre.o /tmp/cc1Tm68F.s\n17.142  riscv64-linux-g  386973 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.145  as               386990 386773   0 \n17.145  aarch64-linux-g  386914 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.146  cc1              386991 386914   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.149  cargo            386995 386951   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.153  as               386994 386894   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.157  cargo            386995 386951   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.160  riscv64-linux-g  386996 386623   0 /usr/local/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.166  rustc            387006 382443   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glib-sys-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_60\", \"v2_62\", \"v2_64\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=a69a2e03c60035a9 ...\n17.168  cc1              386993 386973   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.211  rustc            387009 382443   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gobject-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_62\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=0c135d26d6720fae ...\n17.212  rustc            387025 386995   0 \n17.212  riscv64-linux-g  387012 386623   0 \n17.212  cc1              387014 386996   0 \n17.212  as               387011 386826   0 \n17.212  rustc            387013 386995   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.214  riscv64-linux-g  387022 386623   0 \n17.214  riscv64-linux-g  387016 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.216  cc1              387020 387016   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.216  cc1              387015 387012   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.216  rustc            387010 382443   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gio-sys-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_60\", \"v2_62\", \"v2_64\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=bfbb4b19ffb03a38 ...\n17.217  rustc            387037 386995   0 \n17.217  sh               387034 385794   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth3576eec\n17.217  sed              387036 387034   0 /usr/bin/sed -n s/^driver: //p\n17.217  ethtool          387035 387034   0 /usr/sbin/ethtool -i veth3576eec\n17.219  cc1              387030 387022   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.223  riscv64-linux-g  387029 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.230  cc1              387040 387029   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.232  systemd-sysctl   387043 385794   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3576eec --prefix=/net/ipv4/neigh/veth3576eec --prefix=/net/ipv6/conf/veth3576eec --prefix=/net/ipv6/neigh/veth3576eec\n17.240  as               387045 386901   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/76322f89f5cc2d96-bio.o /tmp/ccroyV0N.s\n17.240  riscv64-linux-g  387042 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.242  aarch64-linux-g  387041 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.248  riscv64-linux-g  387046 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.262  aarch64-linux-g  387047 385733   0 \n17.262  as               387044 386910   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/76322f89f5cc2d96-bio_addr.o /tmp/ccVPWsoy.s\n17.263  riscv64-linux-g  387049 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.268  cc1              387050 387041   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.273  cc1              387064 387042   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.276  cc               387069 387006   0 /tmp/native-trace-381697-1783994295201/shims/cc -m64 /target/debug/build/glib-sys-2525284e1c263402/rustcfpMgFz/symbols.o /target/debug/build/glib-sys-2525284e1c263402/build_script_build-2525284e1c263402.build_script_build.8521860d93b71301-cgu.0.rcgu /target/debug/build/glib-sys-2525284e1c263402/build_script_build-2525284e1c263402.3qavtgvodht1rhm1cxixffnp2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-61ed8a0d01a38046.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-9298195a1d16d775.rlib /target/debug/deps/libtoml_edit-f242072d6460352c.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n17.276  as               387068 386798   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-asn1_lib.o /tmp/ccKCe8S0.s\n17.277  cc               387070 387069   0 /usr/bin/cc -m64 /target/debug/build/glib-sys-2525284e1c263402/rustcfpMgFz/symbols.o /target/debug/build/glib-sys-2525284e1c263402/build_script_build-2525284e1c263402.build_script_build.8521860d93b71301-cgu.0.rcgu /target/debug/build/glib-sys-2525284e1c263402/build_script_build-2525284e1c263402.3qavtgvodht1rhm1cxixffnp2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-61ed8a0d01a38046.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-9298195a1d16d775.rlib /target/debug/deps/libtoml_edit-f242072d6460352c.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n17.281  collect2         387071 387070   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdXbR05.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.281  riscv64-linux-g  387065 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.283  cc1              387053 387046   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.284  cc1              387067 387049   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.288  ld.lld           387072 387071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdXbR05.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/glib-sys-2525284e1c263402/build_script_build-2525284e1c263402 ...\n17.299  rust-lld         387072 387071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdXbR05.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.300  aarch64-linux-g  387062 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.302  as               387073 386914   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/76322f89f5cc2d96-bio_mem.o /tmp/cczzIrhO.s\n17.303  cc1              387063 387047   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.304  as               387076 386902   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.308  as               387075 386996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.313  cc1              387074 387062   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.322  containerd-shim  387078 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b362fde1 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b36 delete\n17.328  aarch64-linux-g  387077 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.330  cc1              387085 387065   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.330  runc             387086 387078   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b362fde --log-format json delete --force 77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b362fde1\n17.339  cc1              387106 387077   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.344  aarch64-linux-g  387092 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.356  cc               387102 387009   0 /tmp/native-trace-381697-1783994295201/shims/cc -m64 /target/debug/build/gobject-sys-3ed278797798766c/rustc6B98Tf/symbols.o /target/debug/build/gobject-sys-3ed278797798766c/build_script_build-3ed278797798766c.build_script_build.3b5774be9f96b899-cgu.0.r /target/debug/build/gobject-sys-3ed278797798766c/build_script_build-3ed278797798766c.e7xjhcf4bl55ce4g4yq62vd45.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-61ed8a0d01a38046.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-9298195a1d16d775.rlib /target/debug/deps/libtoml_edit-f242072d6460352c.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n17.357  as               387110 386884   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-tasn_typ.o /tmp/ccQCXnpy.s\n17.361  runc             387113 380360   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5480da48398a65bac9b22ba0e53df5c888e49ccfc02aa8c039040b7d13d --log-format json --systemd-cgroup kill --all 5480da48398a65bac9b22ba0e53df5c888e49ccfc02aa8c039040b7d13ded259 9\n17.364  aarch64-linux-g  387111 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.366  cc1              387118 387092   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.368  cc1              387122 387111   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.369  as               387120 386834   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.371  as               387112 386849   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-f_string.o /tmp/cciDBtrU.s\n17.374  rustc            387123 386951   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.376  systemd-sysctl   387124 385794   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf0883d8 --prefix=/net/ipv4/neigh/vethf0883d8 --prefix=/net/ipv6/conf/vethf0883d8 --prefix=/net/ipv6/neigh/vethf0883d8\n17.384  rustc            387123 386951   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.385  as               387133 386973   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.390  aarch64-linux-g  387121 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.393  cc               387136 387102   0 /usr/bin/cc -m64 /target/debug/build/gobject-sys-3ed278797798766c/rustc6B98Tf/symbols.o /target/debug/build/gobject-sys-3ed278797798766c/build_script_build-3ed278797798766c.build_script_build.3b5774be9f96b899-cgu.0.r /target/debug/build/gobject-sys-3ed278797798766c/build_script_build-3ed278797798766c.e7xjhcf4bl55ce4g4yq62vd45.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-61ed8a0d01a38046.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-9298195a1d16d775.rlib /target/debug/deps/libtoml_edit-f242072d6460352c.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n17.395  as               387135 387046   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.397  collect2         387138 387136   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU9tOtA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.397  cc1              387137 387121   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.399  ld.lld           387141 387138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU9tOtA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gobject-sys-3ed278797798766c/build_script_build-3ed278797798766c ...\n17.400  rust-lld         387141 387138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU9tOtA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.402  aarch64-linux-g  387134 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.405  runc             387144 380360   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5480da48398a65bac9b22ba0e53df5c888e49ccfc02aa8c039040b7d13d --log-format json --systemd-cgroup delete 5480da48398a65bac9b22ba0e53df5c888e49ccfc02aa8c039040b7d13ded259\n17.414  cc1              387143 387134   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 380962,
  "build_script_target_dir": "guppy-workspace-hack-d70745282d2fb520",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build",
  "pid": 380962,
  "ppid": 380884,
  "root_cargo_pid": 380884,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "_build_script_out_dir": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/out"
}
```

#### Record 16

```json
{
  "crate": "guppy-workspace-hack",
  "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "event_id": "bsrun:6faaa4cb6f1e9d3f:90144a1729e811cb:1f83b711eaf37b7a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
  "out_dir": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
  "success": true,
  "target": null,
  "version": "0.1.0",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:58:30.753301+00:00",
  "crate": "guppy-workspace-hack",
  "version": "0.1.0",
  "architecture": "aarch64",
  "duration_seconds": 24.73514379095286,
  "trace_record_count": 16,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "manifest_path": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 13,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "guppy-workspace-hack",
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
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "workspace_root": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
          "name": "guppy-workspace-hack",
          "version": "0.1.0",
          "manifest_path": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0"
        }
      ],
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 380934,
      "ppid": 380910,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "guppy-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2fa78141aafe9496:9654dcff812e2b1f:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
      "pid": 380934,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "guppy-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2fa78141aafe9496:a6683e4660d86fd9:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
      "pid": 380934,
      "sha256": "192f6872a48e660566208e186c37ddbd9ceee9b2d0abd7cb17aff178d4ab7631",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "guppy-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2fa78141aafe9496:b27b1f8694553276:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
      "pid": 380934,
      "sha256": "829b295fd101748135b1ef845cc60fbd00f0fc7a043d34b01f259a04a4fdb514",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "guppy-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2fa78141aafe9496:936187359bd39079:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
      "pid": 380934,
      "sha256": "e1eb585ff708f37d45fb26c964a78a02775935df07fe3ae974521079afafc758",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "guppy-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2fa78141aafe9496:11353ab5a8a21cd3:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
      "pid": 380934,
      "sha256": "e93c2416ece7b948a5af9ba7f05292e9b07b604de17b32ecd951dba876e0a0fa",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "guppy-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2fa78141aafe9496:abd889a682f5f794:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
      "pid": 380934,
      "sha256": "5c8119db80fdc3221cdd7b5e95dfe3fe5a57e0bd9d55d52caceec543524a68b6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "guppy-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2fa78141aafe9496:8eb88d76d00ab054:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
      "pid": 380934,
      "sha256": "3886925c78c2d7fa134e01cba1c0a98a1d6e7b338372a370584dc488de578b52",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
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
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "cargo_pkg_name": "guppy-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "context_path": "/tmp/native-trace-380513-1783994290717/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-380513-1783994290717/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 380934,
      "ppid": 380910,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
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
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustcSMXyGD/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.1p7p8qr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.1p7p8qr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.1p7p8qr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.1p7p8qr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.1p7p8qr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.1p7p8qr.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-380934-1783994292940330549.map",
      "pid": 380934,
      "ppid": 380910,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-380934-1783994292940330549.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
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
      "parsed_event_count": 1441,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1442,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "p64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.943  cc1              386905 386902   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.947  cc1              386911 386901   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n16.960  aarch64-linux-g  386910 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n16.966  cc1              386912 386906   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.969  rustc            386915 382443   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glib_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glib-macros-0.18.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n16.979  cc1              386916 386910   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n16.983  riscv64-linux-g  386909 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.987  cc1              386919 386909   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.997  as               386921 386796   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.018  as               386925 386898   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.033  as               386926 386891   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ad45968d24b0237e-base64.o /tmp/cciueJM6.s\n17.033  as               386922 386820   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.039  as               386924 386817   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.067  runc             386929 379546   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b36 --log-format json --systemd-cgroup kill --all 77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b362fde1 9\n17.081  as               386935 386909   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.081  containerd-shim  386936 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201f366d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201 delete\n17.083  as               386937 386787   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.086  runc             386944 386936   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201f366 --log-format json delete --force 2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201f366d\n17.088  riscv64-linux-g  386941 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.092  cross            386951 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n17.093  rustc            386952 386951   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.096  riscv64-linux-g  386946 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.096  runc             386956 379546   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b36 --log-format json --systemd-cgroup delete 77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b362fde1\n17.102  rustc            386952 386951   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.102  cc1              386971 386946   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.116  as               386923 386840   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.117  cc1              386955 386941   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.119  as               386927 386830   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.130  as               386979 386906   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.131  rustc            386980 386951   0 /home/xmoe/.cargo/bin/rustc -vV\n17.137  rustc            386980 386951   0 \n17.137  as               386978 386762   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_type.o /tmp/ccpkob4k.s\n17.137  as               386977 386809   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.140  as               386989 386872   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-tasn_fre.o /tmp/cc1Tm68F.s\n17.142  riscv64-linux-g  386973 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.145  as               386990 386773   0 \n17.145  aarch64-linux-g  386914 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.146  cc1              386991 386914   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.149  cargo            386995 386951   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.153  as               386994 386894   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.157  cargo            386995 386951   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n17.160  riscv64-linux-g  386996 386623   0 /usr/local/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.166  rustc            387006 382443   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glib-sys-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_60\", \"v2_62\", \"v2_64\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=a69a2e03c60035a9 ...\n17.168  cc1              386993 386973   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.211  rustc            387009 382443   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gobject-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_62\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=0c135d26d6720fae ...\n17.212  rustc            387025 386995   0 \n17.212  riscv64-linux-g  387012 386623   0 \n17.212  cc1              387014 386996   0 \n17.212  as               387011 386826   0 \n17.212  rustc            387013 386995   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.214  riscv64-linux-g  387022 386623   0 \n17.214  riscv64-linux-g  387016 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.216  cc1              387020 387016   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.216  cc1              387015 387012   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.216  rustc            387010 382443   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gio-sys-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_60\", \"v2_62\", \"v2_64\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=bfbb4b19ffb03a38 ...\n17.217  rustc            387037 386995   0 \n17.217  sh               387034 385794   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth3576eec\n17.217  sed              387036 387034   0 /usr/bin/sed -n s/^driver: //p\n17.217  ethtool          387035 387034   0 /usr/sbin/ethtool -i veth3576eec\n17.219  cc1              387030 387022   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.223  riscv64-linux-g  387029 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.230  cc1              387040 387029   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.232  systemd-sysctl   387043 385794   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3576eec --prefix=/net/ipv4/neigh/veth3576eec --prefix=/net/ipv6/conf/veth3576eec --prefix=/net/ipv6/neigh/veth3576eec\n17.240  as               387045 386901   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/76322f89f5cc2d96-bio.o /tmp/ccroyV0N.s\n17.240  riscv64-linux-g  387042 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.242  aarch64-linux-g  387041 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.248  riscv64-linux-g  387046 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.262  aarch64-linux-g  387047 385733   0 \n17.262  as               387044 386910   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/76322f89f5cc2d96-bio_addr.o /tmp/ccVPWsoy.s\n17.263  riscv64-linux-g  387049 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.268  cc1              387050 387041   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.273  cc1              387064 387042   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.276  cc               387069 387006   0 /tmp/native-trace-381697-1783994295201/shims/cc -m64 /target/debug/build/glib-sys-2525284e1c263402/rustcfpMgFz/symbols.o /target/debug/build/glib-sys-2525284e1c263402/build_script_build-2525284e1c263402.build_script_build.8521860d93b71301-cgu.0.rcgu /target/debug/build/glib-sys-2525284e1c263402/build_script_build-2525284e1c263402.3qavtgvodht1rhm1cxixffnp2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-61ed8a0d01a38046.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-9298195a1d16d775.rlib /target/debug/deps/libtoml_edit-f242072d6460352c.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n17.276  as               387068 386798   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-asn1_lib.o /tmp/ccKCe8S0.s\n17.277  cc               387070 387069   0 /usr/bin/cc -m64 /target/debug/build/glib-sys-2525284e1c263402/rustcfpMgFz/symbols.o /target/debug/build/glib-sys-2525284e1c263402/build_script_build-2525284e1c263402.build_script_build.8521860d93b71301-cgu.0.rcgu /target/debug/build/glib-sys-2525284e1c263402/build_script_build-2525284e1c263402.3qavtgvodht1rhm1cxixffnp2.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-61ed8a0d01a38046.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-9298195a1d16d775.rlib /target/debug/deps/libtoml_edit-f242072d6460352c.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n17.281  collect2         387071 387070   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdXbR05.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.281  riscv64-linux-g  387065 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.283  cc1              387053 387046   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.284  cc1              387067 387049   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.288  ld.lld           387072 387071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdXbR05.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/glib-sys-2525284e1c263402/build_script_build-2525284e1c263402 ...\n17.299  rust-lld         387072 387071   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdXbR05.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.300  aarch64-linux-g  387062 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.302  as               387073 386914   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/76322f89f5cc2d96-bio_mem.o /tmp/cczzIrhO.s\n17.303  cc1              387063 387047   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.304  as               387076 386902   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.308  as               387075 386996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.313  cc1              387074 387062   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.322  containerd-shim  387078 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b362fde1 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b36 delete\n17.328  aarch64-linux-g  387077 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.330  cc1              387085 387065   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.330  runc             387086 387078   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b362fde --log-format json delete --force 77714e741adf5b653a689859260c71771a062ca4093576292184d0f2b362fde1\n17.339  cc1              387106 387077   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.344  aarch64-linux-g  387092 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.356  cc               387102 387009   0 /tmp/native-trace-381697-1783994295201/shims/cc -m64 /target/debug/build/gobject-sys-3ed278797798766c/rustc6B98Tf/symbols.o /target/debug/build/gobject-sys-3ed278797798766c/build_script_build-3ed278797798766c.build_script_build.3b5774be9f96b899-cgu.0.r /target/debug/build/gobject-sys-3ed278797798766c/build_script_build-3ed278797798766c.e7xjhcf4bl55ce4g4yq62vd45.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-61ed8a0d01a38046.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-9298195a1d16d775.rlib /target/debug/deps/libtoml_edit-f242072d6460352c.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n17.357  as               387110 386884   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-tasn_typ.o /tmp/ccQCXnpy.s\n17.361  runc             387113 380360   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5480da48398a65bac9b22ba0e53df5c888e49ccfc02aa8c039040b7d13d --log-format json --systemd-cgroup kill --all 5480da48398a65bac9b22ba0e53df5c888e49ccfc02aa8c039040b7d13ded259 9\n17.364  aarch64-linux-g  387111 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.366  cc1              387118 387092   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.368  cc1              387122 387111   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.369  as               387120 386834   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.371  as               387112 386849   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-f_string.o /tmp/cciDBtrU.s\n17.374  rustc            387123 386951   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.376  systemd-sysctl   387124 385794   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf0883d8 --prefix=/net/ipv4/neigh/vethf0883d8 --prefix=/net/ipv6/conf/vethf0883d8 --prefix=/net/ipv6/neigh/vethf0883d8\n17.384  rustc            387123 386951   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.385  as               387133 386973   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.390  aarch64-linux-g  387121 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.393  cc               387136 387102   0 /usr/bin/cc -m64 /target/debug/build/gobject-sys-3ed278797798766c/rustc6B98Tf/symbols.o /target/debug/build/gobject-sys-3ed278797798766c/build_script_build-3ed278797798766c.build_script_build.3b5774be9f96b899-cgu.0.r /target/debug/build/gobject-sys-3ed278797798766c/build_script_build-3ed278797798766c.e7xjhcf4bl55ce4g4yq62vd45.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-61ed8a0d01a38046.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-9298195a1d16d775.rlib /target/debug/deps/libtoml_edit-f242072d6460352c.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-efb6636ff84aad7a.rlib ...\n17.395  as               387135 387046   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.397  collect2         387138 387136   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU9tOtA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.397  cc1              387137 387121   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.399  ld.lld           387141 387138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU9tOtA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gobject-sys-3ed278797798766c/build_script_build-3ed278797798766c ...\n17.400  rust-lld         387141 387138   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccU9tOtA.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.402  aarch64-linux-g  387134 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.405  runc             387144 380360   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5480da48398a65bac9b22ba0e53df5c888e49ccfc02aa8c039040b7d13d --log-format json --systemd-cgroup delete 5480da48398a65bac9b22ba0e53df5c888e49ccfc02aa8c039040b7d13ded259\n17.414  cc1              387143 387134   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n"
    },
    {
      "argv": [
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 380962,
      "build_script_target_dir": "guppy-workspace-hack-d70745282d2fb520",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build",
      "pid": 380962,
      "ppid": 380884,
      "root_cargo_pid": 380884,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "guppy-workspace-hack",
      "cwd": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "event_id": "bsrun:6faaa4cb6f1e9d3f:90144a1729e811cb:1f83b711eaf37b7a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
      "out_dir": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
      "success": true,
      "target": null,
      "version": "0.1.0",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-aarch64-msjudirm/src/guppy-workspace-hack-0.1.0",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 1655,
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "crate_id": "487324",
    "version_id": "458415",
    "downloads": 9717200,
    "cumulative_downloads": 98836715438,
    "cumulative_share_of_global": 0.3695276619921708,
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
