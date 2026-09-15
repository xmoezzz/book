# `smartstring` `1.0.1`

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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
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
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj",
    "/target/debug/build/smartstring-82c922e517a55c78",
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
      "directory": "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-124882-1783993011668937975.map",
  "pid": 124882,
  "ppid": 124842,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-124882-1783993011668937975.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "workspace_root": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#atty@0.2.14",
      "name": "atty",
      "version": "0.2.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
      "name": "autocfg",
      "version": "1.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-set@0.8.0",
      "name": "bit-set",
      "version": "0.8.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.8.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.8.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-vec@0.8.0",
      "name": "bit-vec",
      "version": "0.8.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.8.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.8.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
      "name": "bitflags",
      "version": "1.3.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.13.0",
      "name": "bitflags",
      "version": "2.13.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.20.3",
      "name": "bumpalo",
      "version": "3.20.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
      "name": "cast",
      "version": "0.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
      "name": "cfg-if",
      "version": "1.0.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@2.34.0",
      "name": "clap",
      "version": "2.34.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.3.6",
      "name": "criterion",
      "version": "0.3.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.4.5",
      "name": "criterion-plot",
      "version": "0.4.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.7",
      "name": "crossbeam-deque",
      "version": "0.8.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.20",
      "name": "crossbeam-epoch",
      "version": "0.9.20",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
      "name": "crossbeam-utils",
      "version": "0.8.22",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv@1.4.0",
      "name": "csv",
      "version": "1.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv-core@0.1.13",
      "name": "csv-core",
      "version": "0.1.13",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
      "name": "either",
      "version": "1.16.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.14",
      "name": "errno",
      "version": "0.3.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.4.1",
      "name": "fastrand",
      "version": "2.4.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fnv@1.0.7",
      "name": "fnv",
      "version": "1.0.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fnv-1.0.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fnv-1.0.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
      "name": "futures-core",
      "version": "0.3.32",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.32",
      "name": "futures-task",
      "version": "0.3.32",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.32",
      "name": "futures-util",
      "version": "0.3.32",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.17",
      "name": "getrandom",
      "version": "0.2.17",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.3.4",
      "name": "getrandom",
      "version": "0.3.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.3.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.3.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.4.3",
      "name": "getrandom",
      "version": "0.4.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.4.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.4.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.3",
      "name": "half",
      "version": "1.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.1.19",
      "name": "hermit-abi",
      "version": "0.1.19",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
      "name": "itertools",
      "version": "0.10.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
      "name": "itoa",
      "version": "1.0.18",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.103",
      "name": "js-sys",
      "version": "0.3.103",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
      "name": "lazy_static",
      "version": "1.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.12.1",
      "name": "linux-raw-sys",
      "version": "0.12.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.12.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.12.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
      "name": "memchr",
      "version": "2.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
      "name": "num-traits",
      "version": "0.2.19",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
      "name": "once_cell",
      "version": "1.21.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.5",
      "name": "oorandom",
      "version": "11.1.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
      "name": "pin-project-lite",
      "version": "0.2.17",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.7",
      "name": "plotters",
      "version": "0.3.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.7",
      "name": "plotters-backend",
      "version": "0.3.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.7",
      "name": "plotters-svg",
      "version": "0.3.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.21",
      "name": "ppv-lite86",
      "version": "0.2.21",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@0.4.30",
      "name": "proc-macro2",
      "version": "0.4.30",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-0.4.30/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-0.4.30"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
      "name": "proc-macro2",
      "version": "1.0.106",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proptest@1.11.0",
      "name": "proptest",
      "version": "1.11.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-1.11.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-1.11.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proptest-derive@0.3.0",
      "name": "proptest-derive",
      "version": "0.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-derive-0.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-derive-0.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quick-error@1.2.3",
      "name": "quick-error",
      "version": "1.2.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quick-error-1.2.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quick-error-1.2.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@0.6.13",
      "name": "quote",
      "version": "0.6.13",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-0.6.13/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-0.6.13"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
      "name": "quote",
      "version": "1.0.46",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#r-efi@5.3.0",
      "name": "r-efi",
      "version": "5.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-5.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-5.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#r-efi@6.0.0",
      "name": "r-efi",
      "version": "6.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-6.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-6.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.8.7",
      "name": "rand",
      "version": "0.8.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.9.5",
      "name": "rand",
      "version": "0.9.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.9.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.9.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.3.1",
      "name": "rand_chacha",
      "version": "0.3.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.9.0",
      "name": "rand_chacha",
      "version": "0.9.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.9.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.9.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.6.4",
      "name": "rand_core",
      "version": "0.6.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.9.5",
      "name": "rand_core",
      "version": "0.9.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.9.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.9.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_xorshift@0.4.0",
      "name": "rand_xorshift",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.12.0",
      "name": "rayon",
      "version": "1.12.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.13.0",
      "name": "rayon-core",
      "version": "1.13.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@1.1.4",
      "name": "rustix",
      "version": "1.1.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-1.1.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-1.1.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.23",
      "name": "rustversion",
      "version": "1.0.23",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rusty-fork@0.3.1",
      "name": "rusty-fork",
      "version": "0.3.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rusty-fork-0.3.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rusty-fork-0.3.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
      "name": "ryu",
      "version": "1.0.23",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
      "name": "same-file",
      "version": "1.0.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
      "name": "serde",
      "version": "1.0.228",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_cbor@0.11.2",
      "name": "serde_cbor",
      "version": "0.11.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
      "name": "serde_core",
      "version": "1.0.228",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
      "name": "serde_derive",
      "version": "1.0.228",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
      "name": "serde_json",
      "version": "1.0.150",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_test@1.0.177",
      "name": "serde_test",
      "version": "1.0.177",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.12",
      "name": "slab",
      "version": "0.4.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12"
    },
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
      "name": "smartstring",
      "version": "1.0.1",
      "manifest_path": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#static_assertions@1.1.0",
      "name": "static_assertions",
      "version": "1.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/static_assertions-1.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/static_assertions-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@0.15.44",
      "name": "syn",
      "version": "0.15.44",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-0.15.44/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-0.15.44"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
      "name": "syn",
      "version": "2.0.118",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tempfile@3.27.0",
      "name": "tempfile",
      "version": "3.27.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tempfile-3.27.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tempfile-3.27.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.11.0",
      "name": "textwrap",
      "version": "0.11.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
      "name": "tinytemplate",
      "version": "1.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unarray@0.1.4",
      "name": "unarray",
      "version": "0.1.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unarray-0.1.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unarray-0.1.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
      "name": "unicode-ident",
      "version": "1.0.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
      "name": "unicode-width",
      "version": "0.1.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-xid@0.1.0",
      "name": "unicode-xid",
      "version": "0.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
      "name": "version_check",
      "version": "0.9.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wait-timeout@0.2.1",
      "name": "wait-timeout",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wait-timeout-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wait-timeout-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
      "name": "walkdir",
      "version": "2.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.1+wasi-snapshot-preview1",
      "name": "wasi",
      "version": "0.11.1+wasi-snapshot-preview1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.1+wasi-snapshot-preview1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.1+wasi-snapshot-preview1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasip2@1.0.4+wasi-0.2.12",
      "name": "wasip2",
      "version": "1.0.4+wasi-0.2.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasip2-1.0.4+wasi-0.2.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasip2-1.0.4+wasi-0.2.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.126",
      "name": "wasm-bindgen",
      "version": "0.2.126",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.126",
      "name": "wasm-bindgen-macro",
      "version": "0.2.126",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.126",
      "name": "wasm-bindgen-macro-support",
      "version": "0.2.126",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.126",
      "name": "wasm-bindgen-shared",
      "version": "0.2.126",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.103",
      "name": "web-sys",
      "version": "0.3.103",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
      "name": "winapi",
      "version": "0.3.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
      "name": "winapi-i686-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
      "name": "winapi-util",
      "version": "0.1.11",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
      "name": "winapi-x86_64-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
      "name": "windows-link",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
      "name": "windows-sys",
      "version": "0.61.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wit-bindgen@0.57.1",
      "name": "wit-bindgen",
      "version": "0.57.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wit-bindgen-0.57.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wit-bindgen-0.57.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy@0.8.54",
      "name": "zerocopy",
      "version": "0.8.54",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.8.54/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.8.54"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy-derive@0.8.54",
      "name": "zerocopy-derive",
      "version": "0.8.54",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-derive-0.8.54/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-derive-0.8.54"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
      "name": "zmij",
      "version": "1.0.23",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23"
    }
  ],
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 124882,
  "ppid": 124842,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "smartstring",
  "cargo_pkg_version": "1.0.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "event_id": "used:cc:dc4dff2313f49fa1:749a48eba25366d0:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
  "pid": 124882,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "smartstring",
  "cargo_pkg_version": "1.0.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "event_id": "used:cc:dc4dff2313f49fa1:e605c83ade274eba:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
  "pid": 124882,
  "sha256": "5cd55c51c32dee68e9ad5958ae4e5981d23beda7ebc38fe97cd0ca6121c7a25f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "smartstring",
  "cargo_pkg_version": "1.0.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "event_id": "used:cc:dc4dff2313f49fa1:71740d771da1d979:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
  "pid": 124882,
  "sha256": "e2867676c2c15f54f77beeac6ce94d1d858eb6fc92597648da5ac54a36390b43",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "smartstring",
  "cargo_pkg_version": "1.0.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "event_id": "used:cc:dc4dff2313f49fa1:a456e27effbd9cda:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
  "pid": 124882,
  "sha256": "88659020c07ea6feb1e6bcf2b7f857101c6057d7c98a7f10974cc638b40d31d8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "smartstring",
  "cargo_pkg_version": "1.0.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "event_id": "used:cc:dc4dff2313f49fa1:46c3df674a1cca30:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
  "pid": 124882,
  "sha256": "6e941cfb569e4c8301ad1622d0b0d262913850b474bd3353bcfb5884291956d2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "smartstring",
  "cargo_pkg_version": "1.0.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "event_id": "used:cc:dc4dff2313f49fa1:e28e6309a79407b5:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
  "pid": 124882,
  "sha256": "7e6ac4586ab55aa2c4e6cff52499db83b2e91440b1e6208f56413d1537ae6f6d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "smartstring",
  "cargo_pkg_version": "1.0.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "event_id": "used:cc:dc4dff2313f49fa1:c13f16a082fcd959:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
  "pid": 124882,
  "sha256": "a170398158d087ed31375e370db1e27001c38aa36b09d9d5563ae49ee1f218f4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "smartstring",
  "cargo_pkg_version": "1.0.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "event_id": "used:cc:dc4dff2313f49fa1:222c5663b03e5891:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
  "pid": 124882,
  "sha256": "3425686ba075ae1b4e20aa49ffeb16fc729e1598c9f847399551878a565e300e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "smartstring",
  "cargo_pkg_version": "1.0.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "event_id": "used:cc:dc4dff2313f49fa1:fbc1caea28d6c1ff:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
  "pid": 124882,
  "sha256": "62de7ab46fb0e396187e070f791310c1e5ca15bbe27ca62a0fd7ec8de454e324",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
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
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "cargo_pkg_name": "smartstring",
  "cargo_pkg_version": "1.0.1",
  "context_path": "/tmp/native-trace-121905-1783993006204/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-121905-1783993006204/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 124882,
  "ppid": 124842,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj",
    "/target/debug/build/smartstring-82c922e517a55c78",
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
      "directory": "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-124882-1783993011668937975.map",
  "pid": 124882,
  "ppid": 124842,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-124882-1783993011668937975.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
    "source": "cargo_manifest_dir"
  }
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

#### Record 16

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 1009,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1011,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.11.rcgu.o /target/debug/deps/rustcwMphmr/rmeta.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.7njala54batedkalypjsqirw8.rcgu.o -Wl,--as-needed ...\n17.427  rustc            130568 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_collections --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_collections-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n17.435  runc             130585 130445   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8 --log-format json --systemd-cgroup start 1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6d\n17.438  rustc            130583 130576   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.446  cc               130592 130578   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcwMphmr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcwMphmr/symbols.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.00.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.01.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.02.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.03.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.04.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.05.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.06.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.07.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.08.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.09.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.10.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.11.rcgu.o /target/debug/deps/rustcwMphmr/rmeta.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.7njala54batedkalypjsqirw8.rcgu.o -Wl,--as-needed ...\n17.449  sh               130488 130445   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.452  cargo            130598 130488   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.457  collect2         130600 130592   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccB174eP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcwMphmr/raw-dylibs ...\n17.466  ld.lld           130604 130600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccB174eP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcwMphmr/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.473  rustc            130609 130478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-0.1.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=b00ab403a7583cb1 ...\n17.475  cargo-native-tr  130598 130488   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.481  rust-lld         130604 130600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccB174eP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n17.484  cargo            130611 130598   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.494  rustc            130614 130576   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"proptest\", \"proptest1\", \"serde\", \"serde1\")) -C metadata=96b42ddf4b1fc252 ...\n17.519  rustc            130625 130611   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.528  rustc            130627 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_locale_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_locale_core-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n17.542  rustc            130653 130611   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.596  cc               130702 130027   0 /tmp/native-trace-119438-1783992999031/shims/cc -Wl,--version-script=/target/debug/deps/rustcF06qJc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcF06qJc/symbols.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.00.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.01.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.02.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.03.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.04.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.05.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.06.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.07.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.08.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.09.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.10.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.11.rcgu.o /target/debug/deps/rustcF06qJc/rmeta.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.7njala54batedkalypjsqirw8.rcgu.o -Wl,--as-needed ...\n17.602  execsnoop        130723 130598   0 /usr/local/bin/execsnoop -t\n17.602  python3          130723 130598   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.611  cc               130717 130702   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcF06qJc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcF06qJc/symbols.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.00.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.01.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.02.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.03.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.04.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.05.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.06.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.07.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.08.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.09.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.10.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.11.rcgu.o /target/debug/deps/rustcF06qJc/rmeta.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.7njala54batedkalypjsqirw8.rcgu.o -Wl,--as-needed ...\n17.624  collect2         130744 130717   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7ANxCr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcF06qJc/raw-dylibs ...\n17.632  ld.lld           130749 130744   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7ANxCr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcF06qJc/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.645  rust-lld         130749 130744   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7ANxCr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.688  cc               130757 130563   0 /tmp/native-trace-129539-1783993023899/shims/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustcaCQaYH/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.1mol87l.rcgu.o ...\n17.722  cc               130758 130757   0 /usr/bin/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustcaCQaYH/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.1mol87l.rcgu.o ...\n17.732  collect2         130772 130758   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cck0Cknw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.751  rust-lld         130773 130772   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cck0Cknw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791 ...\n17.751  ld.lld           130773 130772   0 \n17.769  rustc            130785 130478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"serde\", \"serde1\", \"serde_derive\")) -C metadata=f3b026774ad028ab ...\n17.876  cc               130882 130614   0 /tmp/native-trace-129466-1783993023675/shims/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustchdf6u9/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.08mjb1m.rcgu.o ...\n17.880  cc               130884 130882   0 /usr/bin/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustchdf6u9/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.08mjb1m.rcgu.o ...\n17.887  16               130885 1        0 /proc/self/fd/16 --deserialize 135 --log-level info --log-target journal-or-kmsg\n17.899  collect2         130886 130884   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbYs3vq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.902  ld.lld           130887 130886   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbYs3vq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791 ...\n17.906  rust-lld         130887 130886   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbYs3vq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.909  frpc             130885 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.923  cc               130888 129968   0 /tmp/native-trace-119488-1783992999210/shims/cc -Wl,--version-script=/target/debug/deps/rustcaQfbgB/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcaQfbgB/symbols.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.0.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.1.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.2.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.3.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.4.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.5.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.6.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.7.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.8.rcgu.o /target/debug/deps/rustcaQfbgB/rmeta.o /target/debug/deps/displaydoc-f9585bfde992e81b.9uug477fui7tx0qiq1iloys4r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib ...\n17.923  cc               130896 130888   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcaQfbgB/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcaQfbgB/symbols.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.0.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.1.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.2.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.3.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.4.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.5.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.6.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.7.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.8.rcgu.o /target/debug/deps/rustcaQfbgB/rmeta.o /target/debug/deps/displaydoc-f9585bfde992e81b.9uug477fui7tx0qiq1iloys4r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib ...\n17.931  collect2         130898 130896   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIXL5ax.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libdisplaydoc-f9585bfde992e81b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcaQfbgB/raw-dylibs ...\n17.935  ld.lld           130902 130898   0 \n17.945  rust-lld         130902 130898   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIXL5ax.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdisplaydoc-f9585bfde992e81b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcaQfbgB/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIXL5ax.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdisplaydoc-f9585bfde992e81b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n17.957  cc               130917 130785   0 /tmp/native-trace-129519-1783993023824/shims/cc -m64 /target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-fd5334c415c657e1.rlib /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a ...\n17.961  cc               130919 130917   0 /usr/bin/cc -m64 /target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-fd5334c415c657e1.rlib /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a ...\n17.965  collect2         130920 130919   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciQEFPH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.970  ld.lld           130922 130920   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciQEFPH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5 ...\n17.972  rust-lld         130922 130920   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciQEFPH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.067  build-script-bu  130966 130538   0 /target/debug/build/camino-2e1d3896195e9791/build-script-build\n18.081  rustc            130967 130966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.084  build-script-bu  130969 130576   0 /target/debug/build/camino-2e1d3896195e9791/build-script-build\n18.097  rustc            130971 130969   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.115  rustc            130977 130538   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name camino --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"proptest\", \"proptest1\", \"serde\", \"serde1\")) -C metadata=7287ae35d3f00c9a ...\n18.125  rustc            130980 130576   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name camino --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"proptest\", \"proptest1\", \"serde\", \"serde1\")) -C metadata=2ce690d304317396 ...\n18.129  build-script-bu  130985 130478   0 /target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build\n18.132  rustc            130987 130985   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n18.152  rustc            130994 130985   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_0d78465da66d32c7_0 --crate-type=lib --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/rand_pcg-b90b7fc83d452419/out --emit=llvm-ir --target powerpc64le-unknown-linux-gnu -\n18.158  cc               130992 130032   0 /tmp/native-trace-119438-1783992999031/shims/cc -Wl,--version-script=/target/debug/deps/rustc4sopyL/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc4sopyL/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n18.162  sed              130997 130479   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.165  cat              130999 130479   0 /usr/bin/cat /proc/2240539/stat\n18.169  cat              131005 130479   0 /usr/bin/cat /proc/4193716/stat\n18.189  rustc            131012 130478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_pcg --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"serde\", \"serde1\", \"serde_derive\")) -C metadata=63d2c3b5f5f54470 ...\n18.212  cc               130996 130992   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc4sopyL/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc4sopyL/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n18.227  collect2         131019 130996   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrxjGw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc4sopyL/raw-dylibs ...\n18.230  ld.lld           131020 131019   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrxjGw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc4sopyL/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.230  cc               131018 129954   0 /tmp/native-trace-119488-1783992999210/shims/cc -Wl,--version-script=/target/debug/deps/rustcbMorTD/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcbMorTD/symbols.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.09.rcgu.o /target/debug/deps/rustcbMorTD/rmeta.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.bp02va7nqdc0eyezo355icbn9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n18.232  cc               131021 131018   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcbMorTD/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcbMorTD/symbols.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.09.rcgu.o /target/debug/deps/rustcbMorTD/rmeta.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.bp02va7nqdc0eyezo355icbn9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n18.232  rust-lld         131020 131019   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrxjGw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.296  collect2         131023 131021   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3fa0VU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcbMorTD/raw-dylibs ...\n18.304  ld.lld           131059 131023   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3fa0VU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcbMorTD/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.307  rust-lld         131059 131023   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3fa0VU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n18.408  cc               131084 130025   0 /tmp/native-trace-119438-1783992999031/shims/cc -Wl,--version-script=/target/debug/deps/rustcVwojxF/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcVwojxF/symbols.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.00.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.01.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.02.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.03.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.04.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.05.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.06.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.07.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.08.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.09.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.10.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.11.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.12.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.13.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.14.rcgu.o ...\n18.412  cc               131088 131084   0 \n18.421  cc               131086 130033   0 /tmp/native-trace-119438-1783992999031/shims/cc -Wl,--version-script=/target/debug/deps/rustcC9RuWP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcC9RuWP/symbols.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.09.rcgu.o /target/debug/deps/rustcC9RuWP/rmeta.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.bp02va7nqdc0eyezo355icbn9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n18.424  cc               131090 131086   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcC9RuWP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcC9RuWP/symbols.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.09.rcgu.o /target/debug/deps/rustcC9RuWP/rmeta.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.bp02va7nqdc0eyezo355icbn9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n18.433  collect2         131091 131090   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc8jTCvB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcC9RuWP/raw-dylibs ...\n18.437  ld.lld           131092 131091   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc8jTCvB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcC9RuWP/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.439  collect2         131089 131088   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVTsems.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcVwojxF/raw-dylibs ...\n18.442  ld.lld           131093 131089   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVTsems.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcVwojxF/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.444  rust-lld         131092 131091   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc8jTCvB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.446  rust-lld         131093 131089   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVTsems.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.523  cc               131119 129952   0 /tmp/native-trace-119488-1783992999210/shims/cc -Wl,--version-script=/target/debug/deps/rustcyvHMfq/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcyvHMfq/symbols.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.00.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.01.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.02.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.03.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.04.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.05.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.06.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.07.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.08.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.09.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.10.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.11.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.12.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.13.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.14.rcgu.o ...\n18.526  cc               131140 131119   0 \n18.560  collect2         131143 131140   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccz0eH1l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcyvHMfq/raw-dylibs ...\n18.604  ld.lld           131166 131143   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccz0eH1l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcyvHMfq/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.621  rust-lld         131166 131143   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccz0eH1l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n18.645  cc               131242 129960   0 /tmp/native-trace-119488-1783992999210/shims/cc -Wl,--version-script=/target/debug/deps/rustcV6fcYb/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcV6fcYb/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n18.649  cc               131249 131242   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcV6fcYb/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcV6fcYb/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n18.655  collect2         131250 131249   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLEBuCN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcV6fcYb/raw-dylibs ...\n18.668  ld.lld           131251 131250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLEBuCN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcV6fcYb/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.668  rust-lld         131251 131250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLEBuCN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n18.683  rustc            131253 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0d727ade6b8a1114 ...\n18.848  rustc            131302 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerofrom --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerofrom-0.1.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n18.926  rustc            131311 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name yoke --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yoke-0.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n18.953  rustc            131318 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n"
}
```

#### Record 17

```json
{
  "argv": [
    "/target/debug/build/smartstring-82c922e517a55c78/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 125035,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/smartstring-82c922e517a55c78/build-script-build",
  "pid": 125035,
  "ppid": 124496,
  "root_cargo_pid": 124496,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_build_script_out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out"
}
```

#### Record 18

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 125035,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 125037,
  "ppid": 125035,
  "root_cargo_pid": 124496,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_build_script_out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 19

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_9e88affc8b404251_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/smartstring-0fec260660e10b06/out",
    "--emit=llvm-ir",
    "--target",
    "aarch64-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 125035,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 125041,
  "ppid": 125035,
  "root_cargo_pid": 124496,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_build_script_out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
  "build_script_root_pid": 125035,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 125054,
  "ppid": 125035,
  "root_cargo_pid": 124496,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_build_script_out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 21

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_9e88affc8b404251_1",
    "--crate-type=lib",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/smartstring-0fec260660e10b06/out",
    "--emit=llvm-ir",
    "--target",
    "aarch64-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 125035,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 125062,
  "ppid": 125035,
  "root_cargo_pid": 124496,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_build_script_out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 22

```json
{
  "crate": "smartstring",
  "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "event_id": "bsrun:f3021be2d24bbeab:736d8391d94ae7d6:4bd9bf900cb310d9",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/smartstring-82c922e517a55c78/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
  "out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
  "success": true,
  "target": null,
  "version": "1.0.1",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
    "source": "cwd_prefix"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 125035,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 125037,
  "ppid": 125035,
  "root_cargo_pid": 124496,
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
    "--crate-name",
    "autocfg_9e88affc8b404251_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/smartstring-0fec260660e10b06/out",
    "--emit=llvm-ir",
    "--target",
    "aarch64-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 125035,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 125041,
  "ppid": 125035,
  "root_cargo_pid": 124496,
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
  "build_script_root_pid": 125035,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 125054,
  "ppid": 125035,
  "root_cargo_pid": 124496,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 26

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_9e88affc8b404251_1",
    "--crate-type=lib",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/smartstring-0fec260660e10b06/out",
    "--emit=llvm-ir",
    "--target",
    "aarch64-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 125035,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 125062,
  "ppid": 125035,
  "root_cargo_pid": 124496,
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
  "time": "2026-07-14T01:37:10.171530+00:00",
  "crate": "smartstring",
  "version": "1.0.1",
  "architecture": "aarch64",
  "duration_seconds": 31.26658281078562,
  "trace_record_count": 22,
  "trace_owner_summary": {
    "owner_package_count": 109,
    "owner_packages": [
      {
        "crate": "wasi",
        "version": "0.11.1+wasi-snapshot-preview1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.1+wasi-snapshot-preview1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.1+wasi-snapshot-preview1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.1+wasi-snapshot-preview1/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro-support",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.126",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126/Cargo.toml"
      },
      {
        "crate": "winapi-x86_64-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "winapi-i686-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-shared",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.126",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.126",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126/Cargo.toml"
      },
      {
        "crate": "wasip2",
        "version": "1.0.4+wasi-0.2.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasip2@1.0.4+wasi-0.2.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasip2-1.0.4+wasi-0.2.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasip2-1.0.4+wasi-0.2.12/Cargo.toml"
      },
      {
        "crate": "pin-project-lite",
        "version": "0.2.17",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/Cargo.toml"
      },
      {
        "crate": "static_assertions",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#static_assertions@1.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/static_assertions-1.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/static_assertions-1.1.0/Cargo.toml"
      },
      {
        "crate": "crossbeam-epoch",
        "version": "0.9.20",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.20",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/Cargo.toml"
      },
      {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/Cargo.toml"
      },
      {
        "crate": "plotters-backend",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7/Cargo.toml"
      },
      {
        "crate": "zerocopy-derive",
        "version": "0.8.54",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy-derive@0.8.54",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-derive-0.8.54",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-derive-0.8.54/Cargo.toml"
      },
      {
        "crate": "crossbeam-deque",
        "version": "0.8.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/Cargo.toml"
      },
      {
        "crate": "proptest-derive",
        "version": "0.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proptest-derive@0.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-derive-0.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-derive-0.3.0/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml"
      },
      {
        "crate": "criterion-plot",
        "version": "0.4.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.4.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5/Cargo.toml"
      },
      {
        "crate": "linux-raw-sys",
        "version": "0.12.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.12.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.12.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.12.1/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml"
      },
      {
        "crate": "unicode-width",
        "version": "0.1.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen",
        "version": "0.2.126",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.126",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126/Cargo.toml"
      },
      {
        "crate": "futures-core",
        "version": "0.3.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/Cargo.toml"
      },
      {
        "crate": "futures-task",
        "version": "0.3.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.32",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32/Cargo.toml"
      },
      {
        "crate": "futures-util",
        "version": "0.3.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.32",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml"
      },
      {
        "crate": "rand_xorshift",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_xorshift@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.4.0/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.8.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml"
      },
      {
        "crate": "version_check",
        "version": "0.9.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml"
      },
      {
        "crate": "plotters-svg",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "0.4.30",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@0.4.30",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-0.4.30",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-0.4.30/Cargo.toml"
      },
      {
        "crate": "rustversion",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.23",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23/Cargo.toml"
      },
      {
        "crate": "serde_core",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.150",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml"
      },
      {
        "crate": "serde_test",
        "version": "1.0.177",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_test@1.0.177",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177/Cargo.toml"
      },
      {
        "crate": "tinytemplate",
        "version": "1.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml"
      },
      {
        "crate": "wait-timeout",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wait-timeout@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wait-timeout-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wait-timeout-0.2.1/Cargo.toml"
      },
      {
        "crate": "winapi-util",
        "version": "0.1.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11/Cargo.toml"
      },
      {
        "crate": "windows-link",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.61.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml"
      },
      {
        "crate": "wit-bindgen",
        "version": "0.57.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wit-bindgen@0.57.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wit-bindgen-0.57.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wit-bindgen-0.57.1/Cargo.toml"
      },
      {
        "crate": "hermit-abi",
        "version": "0.1.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.1.19",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19/Cargo.toml"
      },
      {
        "crate": "lazy_static",
        "version": "1.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml"
      },
      {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/Cargo.toml"
      },
      {
        "crate": "ppv-lite86",
        "version": "0.2.21",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.21",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21/Cargo.toml"
      },
      {
        "crate": "quick-error",
        "version": "1.2.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quick-error@1.2.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quick-error-1.2.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quick-error-1.2.3/Cargo.toml"
      },
      {
        "crate": "rand_chacha",
        "version": "0.3.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.3.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/Cargo.toml"
      },
      {
        "crate": "rand_chacha",
        "version": "0.9.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.9.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.9.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.9.0/Cargo.toml"
      },
      {
        "crate": "rayon-core",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.13.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0/Cargo.toml"
      },
      {
        "crate": "serde_cbor",
        "version": "0.11.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_cbor@0.11.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2/Cargo.toml"
      },
      {
        "crate": "unicode-xid",
        "version": "0.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-xid@0.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.1.0/Cargo.toml"
      },
      {
        "crate": "getrandom",
        "version": "0.2.17",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.17",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17/Cargo.toml"
      },
      {
        "crate": "itertools",
        "version": "0.10.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml"
      },
      {
        "crate": "once_cell",
        "version": "1.21.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/Cargo.toml"
      },
      {
        "crate": "rusty-fork",
        "version": "0.3.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rusty-fork@0.3.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rusty-fork-0.3.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rusty-fork-0.3.1/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "2.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.13.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0/Cargo.toml"
      },
      {
        "crate": "criterion",
        "version": "0.3.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.3.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6/Cargo.toml"
      },
      {
        "crate": "csv-core",
        "version": "0.1.13",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv-core@0.1.13",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13/Cargo.toml"
      },
      {
        "crate": "getrandom",
        "version": "0.3.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.3.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.3.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.3.4/Cargo.toml"
      },
      {
        "crate": "getrandom",
        "version": "0.4.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.4.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.4.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.4.3/Cargo.toml"
      },
      {
        "crate": "oorandom",
        "version": "11.1.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5/Cargo.toml"
      },
      {
        "crate": "proptest",
        "version": "1.11.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proptest@1.11.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-1.11.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-1.11.0/Cargo.toml"
      },
      {
        "crate": "rand_core",
        "version": "0.6.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.6.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/Cargo.toml"
      },
      {
        "crate": "rand_core",
        "version": "0.9.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.9.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.9.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.9.5/Cargo.toml"
      },
      {
        "crate": "same-file",
        "version": "1.0.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml"
      },
      {
        "crate": "tempfile",
        "version": "3.27.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tempfile@3.27.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tempfile-3.27.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tempfile-3.27.0/Cargo.toml"
      },
      {
        "crate": "textwrap",
        "version": "0.11.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.11.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0/Cargo.toml"
      },
      {
        "crate": "web-sys",
        "version": "0.3.103",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.103",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103/Cargo.toml"
      },
      {
        "crate": "zerocopy",
        "version": "0.8.54",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy@0.8.54",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.8.54",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.8.54/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "1.3.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/Cargo.toml"
      },
      {
        "crate": "bumpalo",
        "version": "3.20.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.20.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3/Cargo.toml"
      },
      {
        "crate": "fastrand",
        "version": "2.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.4.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1/Cargo.toml"
      },
      {
        "crate": "js-sys",
        "version": "0.3.103",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.103",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103/Cargo.toml"
      },
      {
        "crate": "plotters",
        "version": "0.3.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml"
      },
      {
        "crate": "bit-set",
        "version": "0.8.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-set@0.8.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.8.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.8.0/Cargo.toml"
      },
      {
        "crate": "bit-vec",
        "version": "0.8.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-vec@0.8.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.8.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.8.0/Cargo.toml"
      },
      {
        "crate": "either",
        "version": "1.16.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml"
      },
      {
        "crate": "unarray",
        "version": "0.1.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unarray@0.1.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unarray-0.1.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unarray-0.1.4/Cargo.toml"
      },
      {
        "crate": "walkdir",
        "version": "2.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml"
      },
      {
        "crate": "errno",
        "version": "0.3.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "0.6.13",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@0.6.13",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-0.6.13",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-0.6.13/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml"
      },
      {
        "crate": "rayon",
        "version": "1.12.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.12.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml"
      },
      {
        "crate": "rustix",
        "version": "1.1.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@1.1.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-1.1.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-1.1.4/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml"
      },
      {
        "crate": "atty",
        "version": "0.2.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#atty@0.2.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14/Cargo.toml"
      },
      {
        "crate": "clap",
        "version": "2.34.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@2.34.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml"
      },
      {
        "crate": "r-efi",
        "version": "5.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#r-efi@5.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-5.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-5.3.0/Cargo.toml"
      },
      {
        "crate": "r-efi",
        "version": "6.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#r-efi@6.0.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-6.0.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-6.0.0/Cargo.toml"
      },
      {
        "crate": "slab",
        "version": "0.4.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "0.15.44",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@0.15.44",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-0.15.44",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-0.15.44/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.118",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml"
      },
      {
        "crate": "zmij",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml"
      },
      {
        "crate": "cast",
        "version": "0.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml"
      },
      {
        "crate": "half",
        "version": "1.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3/Cargo.toml"
      },
      {
        "crate": "rand",
        "version": "0.8.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.8.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7/Cargo.toml"
      },
      {
        "crate": "rand",
        "version": "0.9.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.9.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.9.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.9.5/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23/Cargo.toml"
      },
      {
        "crate": "csv",
        "version": "1.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv@1.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0/Cargo.toml"
      },
      {
        "crate": "fnv",
        "version": "1.0.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fnv@1.0.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fnv-1.0.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fnv-1.0.7/Cargo.toml"
      },
      {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "manifest_path": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1/Cargo.toml"
      }
    ],
    "attributed_event_count": 15,
    "unattributed_event_count": 7,
    "owners": [
      {
        "crate": "smartstring",
        "version": "1.0.1",
        "event_count": 15,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 9,
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
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "workspace_root": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#atty@0.2.14",
          "name": "atty",
          "version": "0.2.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atty-0.2.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
          "name": "autocfg",
          "version": "1.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-set@0.8.0",
          "name": "bit-set",
          "version": "0.8.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.8.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.8.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-vec@0.8.0",
          "name": "bit-vec",
          "version": "0.8.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.8.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.8.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@1.3.2",
          "name": "bitflags",
          "version": "1.3.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-1.3.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.13.0",
          "name": "bitflags",
          "version": "2.13.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.20.3",
          "name": "bumpalo",
          "version": "3.20.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.20.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
          "name": "cast",
          "version": "0.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
          "name": "cfg-if",
          "version": "1.0.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@2.34.0",
          "name": "clap",
          "version": "2.34.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-2.34.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.3.6",
          "name": "criterion",
          "version": "0.3.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.3.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.4.5",
          "name": "criterion-plot",
          "version": "0.4.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.4.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.7",
          "name": "crossbeam-deque",
          "version": "0.8.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.20",
          "name": "crossbeam-epoch",
          "version": "0.9.20",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
          "name": "crossbeam-utils",
          "version": "0.8.22",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv@1.4.0",
          "name": "csv",
          "version": "1.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-1.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#csv-core@0.1.13",
          "name": "csv-core",
          "version": "0.1.13",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/csv-core-0.1.13"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.16.0",
          "name": "either",
          "version": "1.16.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.14",
          "name": "errno",
          "version": "0.3.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.4.1",
          "name": "fastrand",
          "version": "2.4.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fnv@1.0.7",
          "name": "fnv",
          "version": "1.0.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fnv-1.0.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fnv-1.0.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
          "name": "futures-core",
          "version": "0.3.32",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-task@0.3.32",
          "name": "futures-task",
          "version": "0.3.32",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-task-0.3.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-util@0.3.32",
          "name": "futures-util",
          "version": "0.3.32",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-util-0.3.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.17",
          "name": "getrandom",
          "version": "0.2.17",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.3.4",
          "name": "getrandom",
          "version": "0.3.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.3.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.3.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.4.3",
          "name": "getrandom",
          "version": "0.4.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.4.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.4.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.3",
          "name": "half",
          "version": "1.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.1.19",
          "name": "hermit-abi",
          "version": "0.1.19",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.1.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
          "name": "itertools",
          "version": "0.10.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
          "name": "itoa",
          "version": "1.0.18",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.103",
          "name": "js-sys",
          "version": "0.3.103",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.103"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
          "name": "lazy_static",
          "version": "1.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.12.1",
          "name": "linux-raw-sys",
          "version": "0.12.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.12.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.12.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
          "name": "memchr",
          "version": "2.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.19",
          "name": "num-traits",
          "version": "0.2.19",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.19"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.21.4",
          "name": "once_cell",
          "version": "1.21.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.5",
          "name": "oorandom",
          "version": "11.1.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
          "name": "pin-project-lite",
          "version": "0.2.17",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.7",
          "name": "plotters",
          "version": "0.3.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.7",
          "name": "plotters-backend",
          "version": "0.3.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.7",
          "name": "plotters-svg",
          "version": "0.3.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.21",
          "name": "ppv-lite86",
          "version": "0.2.21",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.21"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@0.4.30",
          "name": "proc-macro2",
          "version": "0.4.30",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-0.4.30/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-0.4.30"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
          "name": "proc-macro2",
          "version": "1.0.106",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proptest@1.11.0",
          "name": "proptest",
          "version": "1.11.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-1.11.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-1.11.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proptest-derive@0.3.0",
          "name": "proptest-derive",
          "version": "0.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-derive-0.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proptest-derive-0.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quick-error@1.2.3",
          "name": "quick-error",
          "version": "1.2.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quick-error-1.2.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quick-error-1.2.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@0.6.13",
          "name": "quote",
          "version": "0.6.13",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-0.6.13/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-0.6.13"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
          "name": "quote",
          "version": "1.0.46",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#r-efi@5.3.0",
          "name": "r-efi",
          "version": "5.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-5.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-5.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#r-efi@6.0.0",
          "name": "r-efi",
          "version": "6.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-6.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/r-efi-6.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.8.7",
          "name": "rand",
          "version": "0.8.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.9.5",
          "name": "rand",
          "version": "0.9.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.9.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.9.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.3.1",
          "name": "rand_chacha",
          "version": "0.3.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.9.0",
          "name": "rand_chacha",
          "version": "0.9.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.9.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.9.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.6.4",
          "name": "rand_core",
          "version": "0.6.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.9.5",
          "name": "rand_core",
          "version": "0.9.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.9.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.9.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_xorshift@0.4.0",
          "name": "rand_xorshift",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_xorshift-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.12.0",
          "name": "rayon",
          "version": "1.12.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.12.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.13.0",
          "name": "rayon-core",
          "version": "1.13.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.13.0"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@1.1.4",
          "name": "rustix",
          "version": "1.1.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-1.1.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-1.1.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.23",
          "name": "rustversion",
          "version": "1.0.23",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rusty-fork@0.3.1",
          "name": "rusty-fork",
          "version": "0.3.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rusty-fork-0.3.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rusty-fork-0.3.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
          "name": "ryu",
          "version": "1.0.23",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
          "name": "same-file",
          "version": "1.0.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
          "name": "serde",
          "version": "1.0.228",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_cbor@0.11.2",
          "name": "serde_cbor",
          "version": "0.11.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_cbor-0.11.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
          "name": "serde_core",
          "version": "1.0.228",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
          "name": "serde_derive",
          "version": "1.0.228",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
          "name": "serde_json",
          "version": "1.0.150",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_test@1.0.177",
          "name": "serde_test",
          "version": "1.0.177",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#slab@0.4.12",
          "name": "slab",
          "version": "0.4.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/slab-0.4.12"
        },
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
          "name": "smartstring",
          "version": "1.0.1",
          "manifest_path": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#static_assertions@1.1.0",
          "name": "static_assertions",
          "version": "1.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/static_assertions-1.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/static_assertions-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@0.15.44",
          "name": "syn",
          "version": "0.15.44",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-0.15.44/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-0.15.44"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
          "name": "syn",
          "version": "2.0.118",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tempfile@3.27.0",
          "name": "tempfile",
          "version": "3.27.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tempfile-3.27.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tempfile-3.27.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#textwrap@0.11.0",
          "name": "textwrap",
          "version": "0.11.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/textwrap-0.11.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
          "name": "tinytemplate",
          "version": "1.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unarray@0.1.4",
          "name": "unarray",
          "version": "0.1.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unarray-0.1.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unarray-0.1.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
          "name": "unicode-ident",
          "version": "1.0.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-width@0.1.14",
          "name": "unicode-width",
          "version": "0.1.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-width-0.1.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-xid@0.1.0",
          "name": "unicode-xid",
          "version": "0.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-xid-0.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
          "name": "version_check",
          "version": "0.9.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wait-timeout@0.2.1",
          "name": "wait-timeout",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wait-timeout-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wait-timeout-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.5.0",
          "name": "walkdir",
          "version": "2.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.1+wasi-snapshot-preview1",
          "name": "wasi",
          "version": "0.11.1+wasi-snapshot-preview1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.1+wasi-snapshot-preview1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.1+wasi-snapshot-preview1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasip2@1.0.4+wasi-0.2.12",
          "name": "wasip2",
          "version": "1.0.4+wasi-0.2.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasip2-1.0.4+wasi-0.2.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasip2-1.0.4+wasi-0.2.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.126",
          "name": "wasm-bindgen",
          "version": "0.2.126",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.126",
          "name": "wasm-bindgen-macro",
          "version": "0.2.126",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.126",
          "name": "wasm-bindgen-macro-support",
          "version": "0.2.126",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.126",
          "name": "wasm-bindgen-shared",
          "version": "0.2.126",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.126"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.103",
          "name": "web-sys",
          "version": "0.3.103",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.103"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
          "name": "winapi",
          "version": "0.3.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
          "name": "winapi-i686-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
          "name": "winapi-util",
          "version": "0.1.11",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
          "name": "winapi-x86_64-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
          "name": "windows-link",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
          "name": "windows-sys",
          "version": "0.61.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wit-bindgen@0.57.1",
          "name": "wit-bindgen",
          "version": "0.57.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wit-bindgen-0.57.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wit-bindgen-0.57.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy@0.8.54",
          "name": "zerocopy",
          "version": "0.8.54",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.8.54/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-0.8.54"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#zerocopy-derive@0.8.54",
          "name": "zerocopy-derive",
          "version": "0.8.54",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-derive-0.8.54/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerocopy-derive-0.8.54"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
          "name": "zmij",
          "version": "1.0.23",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23"
        }
      ],
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 124882,
      "ppid": 124842,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "smartstring",
      "cargo_pkg_version": "1.0.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "event_id": "used:cc:dc4dff2313f49fa1:749a48eba25366d0:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
      "pid": 124882,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "smartstring",
      "cargo_pkg_version": "1.0.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "event_id": "used:cc:dc4dff2313f49fa1:e605c83ade274eba:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
      "pid": 124882,
      "sha256": "5cd55c51c32dee68e9ad5958ae4e5981d23beda7ebc38fe97cd0ca6121c7a25f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "smartstring",
      "cargo_pkg_version": "1.0.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "event_id": "used:cc:dc4dff2313f49fa1:71740d771da1d979:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
      "pid": 124882,
      "sha256": "e2867676c2c15f54f77beeac6ce94d1d858eb6fc92597648da5ac54a36390b43",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "smartstring",
      "cargo_pkg_version": "1.0.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "event_id": "used:cc:dc4dff2313f49fa1:a456e27effbd9cda:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
      "pid": 124882,
      "sha256": "88659020c07ea6feb1e6bcf2b7f857101c6057d7c98a7f10974cc638b40d31d8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "smartstring",
      "cargo_pkg_version": "1.0.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "event_id": "used:cc:dc4dff2313f49fa1:46c3df674a1cca30:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
      "pid": 124882,
      "sha256": "6e941cfb569e4c8301ad1622d0b0d262913850b474bd3353bcfb5884291956d2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "smartstring",
      "cargo_pkg_version": "1.0.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "event_id": "used:cc:dc4dff2313f49fa1:e28e6309a79407b5:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
      "pid": 124882,
      "sha256": "7e6ac4586ab55aa2c4e6cff52499db83b2e91440b1e6208f56413d1537ae6f6d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "smartstring",
      "cargo_pkg_version": "1.0.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "event_id": "used:cc:dc4dff2313f49fa1:c13f16a082fcd959:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
      "pid": 124882,
      "sha256": "a170398158d087ed31375e370db1e27001c38aa36b09d9d5563ae49ee1f218f4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "smartstring",
      "cargo_pkg_version": "1.0.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "event_id": "used:cc:dc4dff2313f49fa1:222c5663b03e5891:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
      "pid": 124882,
      "sha256": "3425686ba075ae1b4e20aa49ffeb16fc729e1598c9f847399551878a565e300e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "smartstring",
      "cargo_pkg_version": "1.0.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "event_id": "used:cc:dc4dff2313f49fa1:fbc1caea28d6c1ff:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
      "pid": 124882,
      "sha256": "62de7ab46fb0e396187e070f791310c1e5ca15bbe27ca62a0fd7ec8de454e324",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
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
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "cargo_pkg_name": "smartstring",
      "cargo_pkg_version": "1.0.1",
      "context_path": "/tmp/native-trace-121905-1783993006204/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-121905-1783993006204/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 124882,
      "ppid": 124842,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj",
        "/target/debug/build/smartstring-82c922e517a55c78",
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
          "directory": "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/rustcdKSpYj/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1ao9t8m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1ao9t8m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1ao9t8m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1ao9t8m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1ao9t8m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1ao9t8m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1ao9t8m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1ao9t8m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.4.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-124882-1783993011668937975.map",
      "pid": 124882,
      "ppid": 124842,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-124882-1783993011668937975.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
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
      "parsed_event_count": 1009,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1011,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.11.rcgu.o /target/debug/deps/rustcwMphmr/rmeta.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.7njala54batedkalypjsqirw8.rcgu.o -Wl,--as-needed ...\n17.427  rustc            130568 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_collections --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_collections-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n17.435  runc             130585 130445   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8 --log-format json --systemd-cgroup start 1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6d\n17.438  rustc            130583 130576   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.446  cc               130592 130578   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcwMphmr/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcwMphmr/symbols.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.00.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.01.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.02.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.03.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.04.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.05.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.06.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.07.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.08.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.09.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.10.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.11.rcgu.o /target/debug/deps/rustcwMphmr/rmeta.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.7njala54batedkalypjsqirw8.rcgu.o -Wl,--as-needed ...\n17.449  sh               130488 130445   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.452  cargo            130598 130488   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.457  collect2         130600 130592   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccB174eP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcwMphmr/raw-dylibs ...\n17.466  ld.lld           130604 130600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccB174eP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcwMphmr/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.473  rustc            130609 130478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-0.1.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=b00ab403a7583cb1 ...\n17.475  cargo-native-tr  130598 130488   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.481  rust-lld         130604 130600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccB174eP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n17.484  cargo            130611 130598   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.494  rustc            130614 130576   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"proptest\", \"proptest1\", \"serde\", \"serde1\")) -C metadata=96b42ddf4b1fc252 ...\n17.519  rustc            130625 130611   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.528  rustc            130627 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_locale_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_locale_core-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n17.542  rustc            130653 130611   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.596  cc               130702 130027   0 /tmp/native-trace-119438-1783992999031/shims/cc -Wl,--version-script=/target/debug/deps/rustcF06qJc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcF06qJc/symbols.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.00.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.01.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.02.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.03.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.04.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.05.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.06.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.07.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.08.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.09.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.10.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.11.rcgu.o /target/debug/deps/rustcF06qJc/rmeta.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.7njala54batedkalypjsqirw8.rcgu.o -Wl,--as-needed ...\n17.602  execsnoop        130723 130598   0 /usr/local/bin/execsnoop -t\n17.602  python3          130723 130598   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.611  cc               130717 130702   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcF06qJc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcF06qJc/symbols.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.00.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.01.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.02.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.03.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.04.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.05.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.06.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.07.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.08.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.09.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.10.rcgu.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.yoke_derive.42e1eb696bfb3b2c-cgu.11.rcgu.o /target/debug/deps/rustcF06qJc/rmeta.o /target/debug/deps/yoke_derive-ddea45fb60e7fcdf.7njala54batedkalypjsqirw8.rcgu.o -Wl,--as-needed ...\n17.624  collect2         130744 130717   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7ANxCr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcF06qJc/raw-dylibs ...\n17.632  ld.lld           130749 130744   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7ANxCr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcF06qJc/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n17.645  rust-lld         130749 130744   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7ANxCr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libyoke_derive-ddea45fb60e7fcdf.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n17.688  cc               130757 130563   0 /tmp/native-trace-129539-1783993023899/shims/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustcaCQaYH/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.1mol87l.rcgu.o ...\n17.722  cc               130758 130757   0 /usr/bin/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustcaCQaYH/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.1mol87l.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.1mol87l.rcgu.o ...\n17.732  collect2         130772 130758   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cck0Cknw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.751  rust-lld         130773 130772   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cck0Cknw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791 ...\n17.751  ld.lld           130773 130772   0 \n17.769  rustc            130785 130478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"serde\", \"serde1\", \"serde_derive\")) -C metadata=f3b026774ad028ab ...\n17.876  cc               130882 130614   0 /tmp/native-trace-129466-1783993023675/shims/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustchdf6u9/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.08mjb1m.rcgu.o ...\n17.880  cc               130884 130882   0 /usr/bin/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustchdf6u9/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.08mjb1m.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.08mjb1m.rcgu.o ...\n17.887  16               130885 1        0 /proc/self/fd/16 --deserialize 135 --log-level info --log-target journal-or-kmsg\n17.899  collect2         130886 130884   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbYs3vq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.902  ld.lld           130887 130886   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbYs3vq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791 ...\n17.906  rust-lld         130887 130886   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccbYs3vq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.909  frpc             130885 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.923  cc               130888 129968   0 /tmp/native-trace-119488-1783992999210/shims/cc -Wl,--version-script=/target/debug/deps/rustcaQfbgB/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcaQfbgB/symbols.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.0.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.1.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.2.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.3.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.4.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.5.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.6.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.7.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.8.rcgu.o /target/debug/deps/rustcaQfbgB/rmeta.o /target/debug/deps/displaydoc-f9585bfde992e81b.9uug477fui7tx0qiq1iloys4r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib ...\n17.923  cc               130896 130888   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcaQfbgB/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcaQfbgB/symbols.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.0.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.1.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.2.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.3.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.4.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.5.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.6.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.7.rcgu.o /target/debug/deps/displaydoc-f9585bfde992e81b.displaydoc.e43ed702c65211e3-cgu.8.rcgu.o /target/debug/deps/rustcaQfbgB/rmeta.o /target/debug/deps/displaydoc-f9585bfde992e81b.9uug477fui7tx0qiq1iloys4r.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib ...\n17.931  collect2         130898 130896   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIXL5ax.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libdisplaydoc-f9585bfde992e81b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcaQfbgB/raw-dylibs ...\n17.935  ld.lld           130902 130898   0 \n17.945  rust-lld         130902 130898   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIXL5ax.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdisplaydoc-f9585bfde992e81b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcaQfbgB/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIXL5ax.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdisplaydoc-f9585bfde992e81b.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n17.957  cc               130917 130785   0 /tmp/native-trace-129519-1783993023824/shims/cc -m64 /target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-fd5334c415c657e1.rlib /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a ...\n17.961  cc               130919 130917   0 /usr/bin/cc -m64 /target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-fd5334c415c657e1.rlib /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a ...\n17.965  collect2         130920 130919   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciQEFPH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.970  ld.lld           130922 130920   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciQEFPH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5 ...\n17.972  rust-lld         130922 130920   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciQEFPH.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.067  build-script-bu  130966 130538   0 /target/debug/build/camino-2e1d3896195e9791/build-script-build\n18.081  rustc            130967 130966   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.084  build-script-bu  130969 130576   0 /target/debug/build/camino-2e1d3896195e9791/build-script-build\n18.097  rustc            130971 130969   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.115  rustc            130977 130538   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name camino --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"proptest\", \"proptest1\", \"serde\", \"serde1\")) -C metadata=7287ae35d3f00c9a ...\n18.125  rustc            130980 130576   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name camino --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"proptest\", \"proptest1\", \"serde\", \"serde1\")) -C metadata=2ce690d304317396 ...\n18.129  build-script-bu  130985 130478   0 /target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build\n18.132  rustc            130987 130985   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n18.152  rustc            130994 130985   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_0d78465da66d32c7_0 --crate-type=lib --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/rand_pcg-b90b7fc83d452419/out --emit=llvm-ir --target powerpc64le-unknown-linux-gnu -\n18.158  cc               130992 130032   0 /tmp/native-trace-119438-1783992999031/shims/cc -Wl,--version-script=/target/debug/deps/rustc4sopyL/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc4sopyL/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n18.162  sed              130997 130479   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.165  cat              130999 130479   0 /usr/bin/cat /proc/2240539/stat\n18.169  cat              131005 130479   0 /usr/bin/cat /proc/4193716/stat\n18.189  rustc            131012 130478   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_pcg --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"serde\", \"serde1\", \"serde_derive\")) -C metadata=63d2c3b5f5f54470 ...\n18.212  cc               130996 130992   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc4sopyL/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc4sopyL/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n18.227  collect2         131019 130996   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrxjGw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc4sopyL/raw-dylibs ...\n18.230  ld.lld           131020 131019   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrxjGw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc4sopyL/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.230  cc               131018 129954   0 /tmp/native-trace-119488-1783992999210/shims/cc -Wl,--version-script=/target/debug/deps/rustcbMorTD/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcbMorTD/symbols.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.09.rcgu.o /target/debug/deps/rustcbMorTD/rmeta.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.bp02va7nqdc0eyezo355icbn9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n18.232  cc               131021 131018   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcbMorTD/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcbMorTD/symbols.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.09.rcgu.o /target/debug/deps/rustcbMorTD/rmeta.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.bp02va7nqdc0eyezo355icbn9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n18.232  rust-lld         131020 131019   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczrxjGw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.296  collect2         131023 131021   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3fa0VU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcbMorTD/raw-dylibs ...\n18.304  ld.lld           131059 131023   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3fa0VU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcbMorTD/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.307  rust-lld         131059 131023   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3fa0VU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n18.408  cc               131084 130025   0 /tmp/native-trace-119438-1783992999031/shims/cc -Wl,--version-script=/target/debug/deps/rustcVwojxF/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcVwojxF/symbols.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.00.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.01.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.02.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.03.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.04.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.05.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.06.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.07.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.08.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.09.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.10.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.11.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.12.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.13.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.14.rcgu.o ...\n18.412  cc               131088 131084   0 \n18.421  cc               131086 130033   0 /tmp/native-trace-119438-1783992999031/shims/cc -Wl,--version-script=/target/debug/deps/rustcC9RuWP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcC9RuWP/symbols.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.09.rcgu.o /target/debug/deps/rustcC9RuWP/rmeta.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.bp02va7nqdc0eyezo355icbn9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n18.424  cc               131090 131086   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcC9RuWP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcC9RuWP/symbols.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.00.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.01.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.02.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.03.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.04.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.05.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.06.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.07.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.08.rcgu.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.zerovec_derive.6b886e733cf4296e-cgu.09.rcgu.o /target/debug/deps/rustcC9RuWP/rmeta.o /target/debug/deps/zerovec_derive-a73a5db180ff338f.bp02va7nqdc0eyezo355icbn9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-1ec2033142a5fc21.rlib ...\n18.433  collect2         131091 131090   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc8jTCvB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcC9RuWP/raw-dylibs ...\n18.437  ld.lld           131092 131091   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc8jTCvB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcC9RuWP/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.439  collect2         131089 131088   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVTsems.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcVwojxF/raw-dylibs ...\n18.442  ld.lld           131093 131089   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVTsems.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcVwojxF/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.444  rust-lld         131092 131091   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc8jTCvB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerovec_derive-a73a5db180ff338f.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.446  rust-lld         131093 131089   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVTsems.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n18.523  cc               131119 129952   0 /tmp/native-trace-119488-1783992999210/shims/cc -Wl,--version-script=/target/debug/deps/rustcyvHMfq/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcyvHMfq/symbols.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.00.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.01.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.02.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.03.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.04.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.05.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.06.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.07.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.08.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.09.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.10.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.11.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.12.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.13.rcgu.o /target/debug/deps/zerofrom_derive-74aa3c587eb2fd28.zerofrom_derive.7635b2f8e53a6c2f-cgu.14.rcgu.o ...\n18.526  cc               131140 131119   0 \n18.560  collect2         131143 131140   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccz0eH1l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcyvHMfq/raw-dylibs ...\n18.604  ld.lld           131166 131143   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccz0eH1l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcyvHMfq/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.621  rust-lld         131166 131143   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccz0eH1l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libzerofrom_derive-74aa3c587eb2fd28.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n18.645  cc               131242 129960   0 /tmp/native-trace-119488-1783992999210/shims/cc -Wl,--version-script=/target/debug/deps/rustcV6fcYb/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcV6fcYb/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n18.649  cc               131249 131242   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcV6fcYb/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcV6fcYb/symbols.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-115c43b16354d5e6.thiserror_impl.80ab48198703e4e6-cgu.14.rcgu.o ...\n18.655  collect2         131250 131249   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLEBuCN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcV6fcYb/raw-dylibs ...\n18.668  ld.lld           131251 131250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLEBuCN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcV6fcYb/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n18.668  rust-lld         131251 131250   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLEBuCN.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-115c43b16354d5e6.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n18.683  rustc            131253 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0d727ade6b8a1114 ...\n18.848  rustc            131302 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerofrom --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerofrom-0.1.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n18.926  rustc            131311 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name yoke --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yoke-0.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n18.953  rustc            131318 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n"
    },
    {
      "argv": [
        "/target/debug/build/smartstring-82c922e517a55c78/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 125035,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/smartstring-82c922e517a55c78/build-script-build",
      "pid": 125035,
      "ppid": 124496,
      "root_cargo_pid": 124496,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 125035,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 125037,
      "ppid": 125035,
      "root_cargo_pid": 124496,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_9e88affc8b404251_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/smartstring-0fec260660e10b06/out",
        "--emit=llvm-ir",
        "--target",
        "aarch64-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 125035,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 125041,
      "ppid": 125035,
      "root_cargo_pid": 124496,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 125035,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 125054,
      "ppid": 125035,
      "root_cargo_pid": 124496,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_9e88affc8b404251_1",
        "--crate-type=lib",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/smartstring-0fec260660e10b06/out",
        "--emit=llvm-ir",
        "--target",
        "aarch64-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 125035,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 125062,
      "ppid": 125035,
      "root_cargo_pid": 124496,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "smartstring",
      "cwd": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "event_id": "bsrun:f3021be2d24bbeab:736d8391d94ae7d6:4bd9bf900cb310d9",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/smartstring-82c922e517a55c78/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
      "out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
      "success": true,
      "target": null,
      "version": "1.0.1",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-aarch64-6ajo6bkx/src/smartstring-1.0.1",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 125035,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 125037,
      "ppid": 125035,
      "root_cargo_pid": 124496,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_9e88affc8b404251_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/smartstring-0fec260660e10b06/out",
        "--emit=llvm-ir",
        "--target",
        "aarch64-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 125035,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 125041,
      "ppid": 125035,
      "root_cargo_pid": 124496,
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
      "build_script_root_pid": 125035,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 125054,
      "ppid": 125035,
      "root_cargo_pid": 124496,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_9e88affc8b404251_1",
        "--crate-type=lib",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/smartstring-0fec260660e10b06/out",
        "--emit=llvm-ir",
        "--target",
        "aarch64-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 125035,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 125062,
      "ppid": 125035,
      "root_cargo_pid": 124496,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 658,
    "crate": "smartstring",
    "version": "1.0.1",
    "crate_id": "242167",
    "version_id": "521583",
    "downloads": 42653772,
    "cumulative_downloads": 78976748791,
    "cumulative_share_of_global": 0.2952758314878273,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "./build.rs",
    "build_script_exists": true,
    "package_build_field": "./build.rs",
    "build_script_reason": "package_build_path",
    "download_source": "local"
  }
}
```
