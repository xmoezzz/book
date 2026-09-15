# `guppy-workspace-hack` `0.1.0`

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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
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
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-380807-1783994292608294222.map",
  "pid": 380807,
  "ppid": 380786,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-380807-1783994292608294222.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "workspace_root": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
      "name": "guppy-workspace-hack",
      "version": "0.1.0",
      "manifest_path": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0"
    }
  ],
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 380807,
  "ppid": 380786,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2e340ce9418793d7:2aedd05ab4ead74d:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
  "pid": 380807,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2e340ce9418793d7:24b2f2c993ecb1cd:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
  "pid": 380807,
  "sha256": "ff921e0e224003a50fd62de66a97b09d9678c6cf23714a11c0b5156947a12fb8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2e340ce9418793d7:d783cc308b3c2aaa:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
  "pid": 380807,
  "sha256": "d2c86c66993b568c6fcb94484eb8117245dfc92d9f43b857422645d6d764bb11",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2e340ce9418793d7:03f682004f68a4ee:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
  "pid": 380807,
  "sha256": "7c1b108ee5cabf480f6a26db6322897ac35d281bd2a71694928ed9b435ef0304",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2e340ce9418793d7:a7f9b65e7191d467:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
  "pid": 380807,
  "sha256": "93333bd0b438e5c2162e6d0eff21745167516a46393f0958b149e315c96c881e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2e340ce9418793d7:c88876407d96316a:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
  "pid": 380807,
  "sha256": "a089d4990375228b3fddd7590486fba4ca0fec2d95f5d71135bd1431bef22c1a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "event_id": "used:cc:2e340ce9418793d7:98000a060786721e:e832b1c9a034d41b",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
  "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
  "pid": 380807,
  "sha256": "3886925c78c2d7fa134e01cba1c0a98a1d6e7b338372a370584dc488de578b52",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "cargo_pkg_name": "guppy-workspace-hack",
  "cargo_pkg_version": "0.1.0",
  "context_path": "/tmp/native-trace-379779-1783994290016/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-379779-1783994290016/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 380807,
  "ppid": 380786,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb",
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
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
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
      "kind": "object",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-380807-1783994292608294222.map",
  "pid": 380807,
  "ppid": 380786,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-380807-1783994292608294222.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
  "parsed_event_count": 1366,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1367,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.805  cc1              386797 386793   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.854  aarch64-linux-g  386798 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n16.866  cc1              386804 386798   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n16.871  as               386807 386784   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n16.871  as               386805 386732   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_dup.o /tmp/cc1Y5Tl4.s\n16.876  riscv64-linux-g  386796 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.879  cc1              386808 386796   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.884  as               386810 386790   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n16.892  aarch64-linux-g  386802 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n16.896  riscv64-linux-g  386809 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.901  riscv64-linux-g  386812 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.903  cc1              386814 386802   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n16.905  as               386813 386760   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_time.o /tmp/cc1Q0Uq9.s\n16.908  cc1              386818 386812   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.915  cc1              386819 386809   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.916  riscv64-linux-g  386817 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.925  aarch64-linux-g  386816 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n16.928  cc1              386821 386817   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.938  riscv64-linux-g  386820 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.941  as               386811 386738   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_int.o /tmp/ccs3gw4u.s\n16.942  cc1              386822 386816   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n16.944  cc1              386824 386820   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.946  riscv64-linux-g  386823 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.951  cc1              386828 386823   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.958  riscv64-linux-g  386826 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.970  cc1              386829 386826   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.979  riscv64-linux-g  386830 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.991  riscv64-linux-g  386832 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.996  cc1              386833 386830   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.999  as               386835 386726   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_bool.o /tmp/ccuw80KA.s\n17.001  cc1              386836 386832   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.012  riscv64-linux-g  386834 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.026  as               386844 386758   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_strnid.o /tmp/ccnvO4O1.s\n17.032  cc1              386841 386834   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.032  as               386843 386755   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_strex.o /tmp/ccswzDoM.s\n17.037  riscv64-linux-g  386840 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.051  aarch64-linux-g  386845 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.053  as               386846 386802   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-asn1_par.o /tmp/ccpeSLcl.s\n17.059  cc1              386848 386845   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.062  aarch64-linux-g  386849 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.064  as               386831 386781   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.065  cc1              386851 386840   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.067  as               386850 386753   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_octet.o /tmp/ccElMeIE.s\n17.074  cc1              386854 386849   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.087  aarch64-linux-g  386853 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.091  as               386857 386764   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_utctm.o /tmp/cctkBqRu.s\n17.099  aarch64-linux-g  386859 385733   0 \n17.106  as               386855 386749   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_object.o /tmp/ccTFIYQk.s\n17.110  cc1              386862 386859   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.113  runc             386864 379633   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201 --log-format json --systemd-cgroup kill --all 2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201f366d 9\n17.113  aarch64-linux-g  386861 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.118  cc1              386858 386853   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.122  as               386871 386812   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.142  cc1              386867 386861   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.154  as               386874 386793   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.157  runc             386875 379633   0 \n17.158  aarch64-linux-g  386872 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.161  as               386873 386746   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_mbstr.o /tmp/ccrCMht8.s\n17.162  cc1              386877 386872   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.169  as               386882 386780   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.171  aarch64-linux-g  386881 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.178  cc1              386886 386881   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.180  aarch64-linux-g  386884 385733   0 \n17.180  as               386885 386832   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.183  as               386887 386845   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-f_int.o /tmp/ccv24sBB.s\n17.189  aarch64-linux-g  386888 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.192  riscv64-linux-g  386889 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.194  cc1              386893 386888   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.197  cc1              386892 386884   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.200  as               386896 386823   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.203  as               386895 386782   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.206  aarch64-linux-g  386891 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.209  riscv64-linux-g  386894 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.214  cc1              386897 386889   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.214  cc1              386899 386894   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.222  cc1              386900 386891   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.223  riscv64-linux-g  386898 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.227  cc1              386903 386898   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.230  riscv64-linux-g  386902 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.234  riscv64-linux-g  386904 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.237  as               386907 386816   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-asn_pack.o /tmp/ccaHf0pn.s\n17.244  cc1              386908 386904   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.249  aarch64-linux-g  386901 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.249  riscv64-linux-g  386906 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.254  cc1              386905 386902   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.258  cc1              386911 386901   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.271  aarch64-linux-g  386910 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.277  cc1              386912 386906   0 \n17.280  rustc            386915 382443   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glib_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glib-macros-0.18.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n17.290  cc1              386916 386910   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.292  riscv64-linux-g  386909 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.298  cc1              386919 386909   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.306  as               386921 386796   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.331  as               386925 386898   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.347  as               386922 386820   0 \n17.347  as               386926 386891   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ad45968d24b0237e-base64.o /tmp/cciueJM6.s\n17.350  as               386924 386817   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 380828,
  "build_script_target_dir": "guppy-workspace-hack-d70745282d2fb520",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build",
  "pid": 380828,
  "ppid": 380763,
  "root_cargo_pid": 380763,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "_build_script_out_dir": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/out"
}
```

#### Record 16

```json
{
  "crate": "guppy-workspace-hack",
  "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "event_id": "bsrun:a7bb96d6b0596e23:90144a1729e811cb:1f83b711eaf37b7a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
  "out_dir": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
  "success": true,
  "target": null,
  "version": "0.1.0",
  "_owner": {
    "crate": "guppy-workspace-hack",
    "version": "0.1.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
    "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:58:30.319020+00:00",
  "crate": "guppy-workspace-hack",
  "version": "0.1.0",
  "architecture": "riscv64",
  "duration_seconds": 24.144066625274718,
  "trace_record_count": 16,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "manifest_path": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "workspace_root": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
          "name": "guppy-workspace-hack",
          "version": "0.1.0",
          "manifest_path": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0"
        }
      ],
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 380807,
      "ppid": 380786,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2e340ce9418793d7:2aedd05ab4ead74d:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
      "pid": 380807,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2e340ce9418793d7:24b2f2c993ecb1cd:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
      "pid": 380807,
      "sha256": "ff921e0e224003a50fd62de66a97b09d9678c6cf23714a11c0b5156947a12fb8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2e340ce9418793d7:d783cc308b3c2aaa:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
      "pid": 380807,
      "sha256": "d2c86c66993b568c6fcb94484eb8117245dfc92d9f43b857422645d6d764bb11",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2e340ce9418793d7:03f682004f68a4ee:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
      "pid": 380807,
      "sha256": "7c1b108ee5cabf480f6a26db6322897ac35d281bd2a71694928ed9b435ef0304",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2e340ce9418793d7:a7f9b65e7191d467:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
      "pid": 380807,
      "sha256": "93333bd0b438e5c2162e6d0eff21745167516a46393f0958b149e315c96c881e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2e340ce9418793d7:c88876407d96316a:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
      "pid": 380807,
      "sha256": "a089d4990375228b3fddd7590486fba4ca0fec2d95f5d71135bd1431bef22c1a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "event_id": "used:cc:2e340ce9418793d7:98000a060786721e:e832b1c9a034d41b",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520",
      "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
      "pid": 380807,
      "sha256": "3886925c78c2d7fa134e01cba1c0a98a1d6e7b338372a370584dc488de578b52",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "cargo_pkg_name": "guppy-workspace-hack",
      "cargo_pkg_version": "0.1.0",
      "context_path": "/tmp/native-trace-379779-1783994290016/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-379779-1783994290016/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 380807,
      "ppid": 380786,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb",
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
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
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/rustciZFVRb/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.0hxdaa5s1dfwotswblq5wesjo.0u4ipor.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.400nadousl1ff5oolyiev5znb.0u4ipor.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.46gfjh5j1cl53jbi53yy3lq4v.0u4ipor.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.7zhuzv76pyir71k9gd6wc5yf0.0u4ipor.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.d9c7brtz8icda2tq4huco881m.0u4ipor.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520",
          "kind": "object",
          "path": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build_script_build-d70745282d2fb520.5evv551d42lzo208b7fohi2ge.0u4ipor.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-380807-1783994292608294222.map",
      "pid": 380807,
      "ppid": 380786,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-380807-1783994292608294222.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
      "parsed_event_count": 1366,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1367,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.805  cc1              386797 386793   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.854  aarch64-linux-g  386798 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n16.866  cc1              386804 386798   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n16.871  as               386807 386784   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n16.871  as               386805 386732   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_dup.o /tmp/cc1Y5Tl4.s\n16.876  riscv64-linux-g  386796 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.879  cc1              386808 386796   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.884  as               386810 386790   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n16.892  aarch64-linux-g  386802 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n16.896  riscv64-linux-g  386809 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.901  riscv64-linux-g  386812 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.903  cc1              386814 386802   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n16.905  as               386813 386760   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_time.o /tmp/cc1Q0Uq9.s\n16.908  cc1              386818 386812   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.915  cc1              386819 386809   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.916  riscv64-linux-g  386817 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.925  aarch64-linux-g  386816 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n16.928  cc1              386821 386817   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.938  riscv64-linux-g  386820 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.941  as               386811 386738   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_int.o /tmp/ccs3gw4u.s\n16.942  cc1              386822 386816   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n16.944  cc1              386824 386820   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.946  riscv64-linux-g  386823 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.951  cc1              386828 386823   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.958  riscv64-linux-g  386826 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.970  cc1              386829 386826   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.979  riscv64-linux-g  386830 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.991  riscv64-linux-g  386832 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n16.996  cc1              386833 386830   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n16.999  as               386835 386726   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_bool.o /tmp/ccuw80KA.s\n17.001  cc1              386836 386832   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.012  riscv64-linux-g  386834 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.026  as               386844 386758   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_strnid.o /tmp/ccnvO4O1.s\n17.032  cc1              386841 386834   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.032  as               386843 386755   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_strex.o /tmp/ccswzDoM.s\n17.037  riscv64-linux-g  386840 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.051  aarch64-linux-g  386845 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.053  as               386846 386802   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-asn1_par.o /tmp/ccpeSLcl.s\n17.059  cc1              386848 386845   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.062  aarch64-linux-g  386849 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.064  as               386831 386781   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.065  cc1              386851 386840   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.067  as               386850 386753   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_octet.o /tmp/ccElMeIE.s\n17.074  cc1              386854 386849   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.087  aarch64-linux-g  386853 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.091  as               386857 386764   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_utctm.o /tmp/cctkBqRu.s\n17.099  aarch64-linux-g  386859 385733   0 \n17.106  as               386855 386749   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_object.o /tmp/ccTFIYQk.s\n17.110  cc1              386862 386859   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.113  runc             386864 379633   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201 --log-format json --systemd-cgroup kill --all 2c8307e51ad12c1c18b74999cb532d60e136bf7c66bc186115f1863f201f366d 9\n17.113  aarch64-linux-g  386861 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.118  cc1              386858 386853   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.122  as               386871 386812   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.142  cc1              386867 386861   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.154  as               386874 386793   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.157  runc             386875 379633   0 \n17.158  aarch64-linux-g  386872 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.161  as               386873 386746   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-a_mbstr.o /tmp/ccrCMht8.s\n17.162  cc1              386877 386872   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.169  as               386882 386780   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.171  aarch64-linux-g  386881 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.178  cc1              386886 386881   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.180  aarch64-linux-g  386884 385733   0 \n17.180  as               386885 386832   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.183  as               386887 386845   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-f_int.o /tmp/ccv24sBB.s\n17.189  aarch64-linux-g  386888 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.192  riscv64-linux-g  386889 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.194  cc1              386893 386888   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.197  cc1              386892 386884   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.200  as               386896 386823   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.203  as               386895 386782   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.206  aarch64-linux-g  386891 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.209  riscv64-linux-g  386894 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.214  cc1              386897 386889   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.214  cc1              386899 386894   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.222  cc1              386900 386891   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.223  riscv64-linux-g  386898 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.227  cc1              386903 386898   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.230  riscv64-linux-g  386902 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.234  riscv64-linux-g  386904 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.237  as               386907 386816   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/bc1b343226bc6a17-asn_pack.o /tmp/ccaHf0pn.s\n17.244  cc1              386908 386904   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.249  aarch64-linux-g  386901 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.249  riscv64-linux-g  386906 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.254  cc1              386905 386902   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.258  cc1              386911 386901   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.271  aarch64-linux-g  386910 385733   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library ...\n17.277  cc1              386912 386906   0 \n17.280  rustc            386915 382443   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glib_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glib-macros-0.18.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n17.290  cc1              386916 386910   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultiarch aarch64-linux-gnu -D_REENTRANT -D _XOPEN_SOURCE=700 -D ...\n17.292  riscv64-linux-g  386909 386623   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include ...\n17.298  cc1              386919 386909   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -imultilib . -imultiarch riscv64-linux-gnu -D_REENTRANT -D ...\n17.306  as               386921 386796   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.331  as               386925 386898   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n17.347  as               386922 386820   0 \n17.347  as               386926 386891   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-aarch64-ujeoe4e6/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/aws-lc-sys-5f1cc6382e2c660a/out/ad45968d24b0237e-base64.o /tmp/cciueJM6.s\n17.350  as               386924 386817   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/generated-include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/s2n-bignum/s2n-bignum-imported/include -I /tmp/crate-build-riscv64-6dkr_r1r/src/aws-lc-sys-0.30.0/aws-lc/third_party/jitterentropy/jitterentropy-library --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 ...\n"
    },
    {
      "argv": [
        "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 380828,
      "build_script_target_dir": "guppy-workspace-hack-d70745282d2fb520",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build",
      "pid": 380828,
      "ppid": 380763,
      "root_cargo_pid": 380763,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "guppy-workspace-hack",
      "cwd": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "event_id": "bsrun:a7bb96d6b0596e23:90144a1729e811cb:1f83b711eaf37b7a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
      "out_dir": "/target/debug/build/guppy-workspace-hack-d70745282d2fb520/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
      "success": true,
      "target": null,
      "version": "0.1.0",
      "_owner": {
        "crate": "guppy-workspace-hack",
        "version": "0.1.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0#guppy-workspace-hack@0.1.0",
        "manifest_dir": "/tmp/crate-build-riscv64-007_v8i_/src/guppy-workspace-hack-0.1.0",
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
