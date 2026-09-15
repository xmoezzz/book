# `smartstring` `1.0.1`

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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3",
    "/target/debug/build/smartstring-82c922e517a55c78",
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
      "directory": "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-127258-1783993017266255748.map",
  "pid": 127258,
  "ppid": 127226,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-127258-1783993017266255748.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "workspace_root": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1"
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
      "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
      "name": "smartstring",
      "version": "1.0.1",
      "manifest_path": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1"
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
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 127258,
  "ppid": 127226,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "event_id": "used:cc:22dbc809832df36d:ec6ebbd7e4ff9d1c:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
  "pid": 127258,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "event_id": "used:cc:22dbc809832df36d:1fd6a2a55b1e0e64:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
  "pid": 127258,
  "sha256": "2fa666dc91f31bcc9ecbf9b79b035b7a2cc61d2135563ffd9b25da9568bd9827",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "event_id": "used:cc:22dbc809832df36d:90f1fa63469f029b:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
  "pid": 127258,
  "sha256": "22f1d122c0407a66d79343639c6a5859bc8b8cd5b8199044b270ce1a5ee27de5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "event_id": "used:cc:22dbc809832df36d:71563c95771de99c:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
  "pid": 127258,
  "sha256": "aab45017d78caf1d5a5dfc404fb71a93139be5b9c855808cfc39d435faa5ceb8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "event_id": "used:cc:22dbc809832df36d:7c6714830c1a9177:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
  "pid": 127258,
  "sha256": "0824212ea377725cbeb9b08ae84b54ec3057ac4fcfb138e77834ebde058ee084",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "event_id": "used:cc:22dbc809832df36d:cee1fe5052e40018:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
  "pid": 127258,
  "sha256": "3b92a3ed1da4a2386e4689b63d2419f4635a64eed61c9a5f80c76d337bca3cfd",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "event_id": "used:cc:22dbc809832df36d:f22bf095004ccac0:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
  "pid": 127258,
  "sha256": "939af0360a8c0b8810710e9d8406239b01463a08796c8dd9f9b39fd96876275d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "event_id": "used:cc:22dbc809832df36d:86771fb08a28c15f:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
  "pid": 127258,
  "sha256": "4e31e1b0e99890fd6b74d4e97d346c63686d04aa5adcfe5b041fcb571ec4738f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "event_id": "used:cc:22dbc809832df36d:15bca158cf83f5f8:e2b4f7e6daceb981",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
  "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
  "pid": 127258,
  "sha256": "62de7ab46fb0e396187e070f791310c1e5ca15bbe27ca62a0fd7ec8de454e324",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "cargo_pkg_name": "smartstring",
  "cargo_pkg_version": "1.0.1",
  "context_path": "/tmp/native-trace-124567-1783993011081/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-124567-1783993011081/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 127258,
  "ppid": 127226,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
    "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3",
    "/target/debug/build/smartstring-82c922e517a55c78",
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
      "directory": "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/smartstring-82c922e517a55c78",
      "kind": "object",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-127258-1783993017266255748.map",
  "pid": 127258,
  "ppid": 127226,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-127258-1783993017266255748.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
  "parsed_event_count": 902,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 904,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": ".69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4e81e20256362857 ...\n13.959  runc             131360 121759   0 \n13.976  rustc            131374 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name yoke --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yoke-0.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n13.996  rustc            131384 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerovec --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerovec-0.11.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.003  rustc            131388 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerotrie --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerotrie-0.2.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.111  rustc            131402 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.113  rustc            131403 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.124  rustc            131409 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerovec --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerovec-0.11.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.126  rustc            131410 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerotrie --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerotrie-0.2.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.165  containerd-shim  131425 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 785747dfac080db39516e6a9929e61ce4a3f2cb792a5a96f5d4af5076e54195d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785747dfac080db39516e6a9929e61ce4a3f2cb792a5a96f5d4af5076e5 delete\n14.170  runc             131432 131425   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785747dfac080db39516e6a9929e61ce4a3f2cb792a5a96f5d4af5076e54195 --log-format json delete --force 785747dfac080db39516e6a9929e61ce4a3f2cb792a5a96f5d4af5076e54195d\n14.187  rustc            131439 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n14.222  systemd-sysctl   131446 130420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4cb96b --prefix=/net/ipv4/neigh/vethf4cb96b --prefix=/net/ipv6/conf/vethf4cb96b --prefix=/net/ipv6/neigh/vethf4cb96b\n14.476  git              131466 2235138   0 /usr/bin/git config --get commit.template\n14.496  git              131467 2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n14.516  git              131473 2235138   0 /usr/bin/git status -z -uall\n14.539  git              131475 2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n14.553  rustc            131483 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tinystr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinystr-0.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.562  rustc            131484 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name potential_utf --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/potential_utf-0.1.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.650  rustc            131502 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_collections --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_collections-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.713  rustc            131520 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tinystr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinystr-0.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.714  rustc            131518 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_urlencoded --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_urlencoded-0.7.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=78a0ef8aa432b300 ...\n14.714  rustc            131519 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_qs --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_qs-0.8.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"actix\", \"actix-web\", \"actix-web2\", \"actix2\", \"default\", \"futures\", \"tracing\", \"warp\", \"warp-framework\")) ...\n14.726  rustc            131517 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name potential_utf --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/potential_utf-0.1.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.726  rustc            131525 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_locale_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_locale_core-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.810  rustc            131549 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_collections --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_collections-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.861  rustc            131559 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_locale_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_locale_core-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.105  16               131585 1        0 /proc/self/fd/16 --deserialize 147 --log-level info --log-target journal-or-kmsg\n15.111  16               131587 1        0 /proc/self/fd/16 --deserialize 161 --log-level info --log-target journal-or-kmsg\n15.254  rustc            131608 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna_adapter --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna_adapter-1.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"compiled_data\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiled_data\")) ...\n15.291  cc               131612 129959   0 /tmp/native-trace-119488-1783992999210/shims/cc -Wl,--version-script=/target/debug/deps/rustc89Iqr2/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc89Iqr2/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n15.297  cc               131617 131612   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc89Iqr2/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc89Iqr2/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n15.307  collect2         131620 131617   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDngMYh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc89Iqr2/raw-dylibs ...\n15.309  ld.lld           131621 131620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDngMYh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc89Iqr2/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.316  rust-lld         131621 131620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDngMYh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n15.343  rustc            131625 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"compiled_data\" --cfg feature=\"std\" ...\n15.354  systemd-coredum  131585 1        0 /usr/lib/systemd/systemd-coredump\n15.356  drkonqi-coredum  131587 1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 901-131583-0\n15.411  cc               131647 130034   0 /tmp/native-trace-119438-1783992999031/shims/cc -Wl,--version-script=/target/debug/deps/rustcUMVHHm/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcUMVHHm/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n15.413  cc               131648 131647   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcUMVHHm/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcUMVHHm/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n15.417  collect2         131649 131648   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Ir7KP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcUMVHHm/raw-dylibs ...\n15.418  ld.lld           131650 131649   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Ir7KP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcUMVHHm/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.421  rust-lld         131650 131649   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Ir7KP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.517  cross            131676 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.519  rustc            131679 131676   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.525  rustc            131679 131676   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.537  rustc            131693 131676   0 /home/xmoe/.cargo/bin/rustc -vV\n15.538  rustc            131690 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n15.544  rustc            131693 131676   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.554  cargo            131706 131676   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.560  cargo            131706 131676   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.571  rustc            131715 131706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.583  rustc            131721 131706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.585  rustc            131720 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name url --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/url-2.5.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"std\" ...\n15.596  rustc            131734 131706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.601  rustc            131730 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.605  rustc            131735 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n15.621  rustc            131745 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.808  abrt-server      131779 1118     0 /usr/bin/abrt-server -s\n15.810  9                131780 4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n15.828  drkonqi-coredum  131780 4003047   0 /usr/libexec/drkonqi-coredump-launcher\n15.835  abrt-handle-eve  131781 131779   0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:37:11.649421-121589\n15.853  sh               131788 131781   0 /bin/sh -c abrt-action-save-package-data\\n\n15.855  rustc            131786 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.855  rustc            131787 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.856  abrt-action-sav  131788 131781   0 /usr/bin/abrt-action-save-package-data\n15.875  rustc            131804 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.879  rustc            131805 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.913  runc             131813 121618   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed --log-format json --systemd-cgroup kill --all c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed10eeb 9\n15.931  runc             131819 121618   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed --log-format json --systemd-cgroup delete c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed10eeb\n15.934  sh               131824 131781   0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n15.939  cat              131827 131825   0 /usr/bin/cat uid\n15.939  cut              131826 131824   0 /usr/bin/cut -d: -f1\n15.943  getent           131825 131824   0 /usr/bin/getent passwd 1000\n15.947  lscpu            131828 131824   0 /usr/bin/lscpu\n15.966  sh               131829 131781   0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n15.968  runlevel         131830 131829   0 /usr/bin/runlevel\n15.984  sh               131831 131781   0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n15.986  grep             131832 131831   0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n15.989  grep             131833 131831   0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n15.992  grep             131834 131831   0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n15.995  abrt-action-cor  131835 131831   0 /usr/libexec/abrt-action-coredump -x\n16.043  cargo            131836 130598   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n16.058  rustc            131842 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_urlencoded --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_urlencoded-0.7.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=7bdfecc0fabf6ec6 ...\n16.058  rustc            131841 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_qs --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_qs-0.8.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"actix\", \"actix-web\", \"actix-web2\", \"actix2\", \"default\", \"futures\", \"tracing\", \"warp\", \"warp-framework\")) ...\n16.062  rustc            131843 131836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.090  abrt-action-gen  131854 131831   0 /usr/bin/abrt-action-generate-core-backtrace\n16.115  rustc            131858 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name http_types --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-std\" --cfg feature=\"cookie\" --cfg feature=\"cookie-secure\" ...\n16.132  rustc            131863 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_urlencoded --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_urlencoded-0.7.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=04dc41fade5f6b3d ...\n16.135  rustc            131865 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_qs --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_qs-0.8.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"actix\", \"actix-web\", \"actix-web2\", \"actix2\", \"default\", \"futures\", \"tracing\", \"warp\", \"warp-framework\")) ...\n16.139  containerd-shim  131873 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed10eeb -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed delete\n16.144  runc             131883 131873   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed10ee --log-format json delete --force c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed10eeb\n16.155  cross            131892 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n16.157  rustc            131894 131892   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.169  rustc            131894 131892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.172  abrt-action-ana  131907 131831   0 /usr/bin/abrt-action-analyze-vulnerability\n16.176  eu-readelf       131909 131908   0 /usr/bin/eu-readelf -n coredump\n16.176  grep             131910 131908   0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n16.178  sed              131911 131908   0 /usr/bin/sed s/[^0-9]//g\n16.200  gdb              131921 131913   0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n16.204  rustc            131923 131892   0 /home/xmoe/.cargo/bin/rustc -vV\n16.214  rustc            131923 131892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.215  sh               131932 130420   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth32e8199\n16.217  sed              131936 131932   0 /usr/bin/sed -n s/^driver: //p\n16.218  ethtool          131935 131932   0 /usr/sbin/ethtool -i veth32e8199\n16.237  systemd-sysctl   131941 130420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth32e8199 --prefix=/net/ipv4/neigh/veth32e8199 --prefix=/net/ipv6/conf/veth32e8199 --prefix=/net/ipv6/neigh/veth32e8199\n16.241  iconv            131943 131921   0 /usr/bin/iconv -l\n16.256  cargo            131955 131892   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.265  cargo            131955 131892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.303  rustc            131969 131955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.316  rustc            131974 131955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.332  rustc            131978 131955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.334  rustup           131979 120100   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.385  abrt-action-ana  131994 131831   0 /usr/bin/abrt-action-analyze-c\n16.397  eu-unstrip       131995 131994   0 /usr/bin/eu-unstrip --core=./coredump -n\n16.415  abrt-action-lis  131996 131831   0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n16.472  cat              132002 132001   0 /usr/bin/cat executable\n16.474  cat              132005 132001   0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:37:11.649421-121589/uid\n16.475  journalctl       132006 132001   0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n16.488  abrt-action-cor  132008 131831   0 /usr/libexec/abrt-action-coredump -r\n16.552  abrt-handle-eve  132014 131779   0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.567  sh               132016 132014   0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n16.569  dbus-send        132016 132014   0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.572  sh               132017 132014   0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n16.574  abrt-action-not  132018 132017   0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.634  16               132020 1        0 /proc/self/fd/16 --deserialize 137 --log-level info --log-target journal-or-kmsg\n16.648  abrt-dbus        132020 1        0 /usr/sbin/abrt-dbus -t133\n16.690  sh               132025 132018   0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n16.692  reporter-system  132025 132018   0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n16.747  rustc            132031 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna_adapter --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna_adapter-1.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"compiled_data\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiled_data\")) ...\n16.785  rustc            132042 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna_adapter --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna_adapter-1.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"compiled_data\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiled_data\")) ...\n16.786  rustc            132046 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"compiled_data\" --cfg feature=\"std\" ...\n16.838  rustc            132061 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"compiled_data\" --cfg feature=\"std\" ...\n16.924  rustc            132067 131706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.959  rustc            132069 131955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.972  sh               132074 2147557   0 /bin/sh -c which ps\n16.973  which            132074 2147557   0 /usr/bin/which ps\n16.976  sh               132076 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.977  rustc            132075 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name url --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/url-2.5.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"std\" ...\n16.979  ps               132076 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.004  sh               132082 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.006  cpuUsage.sh      132082 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.008  sed              132084 132082   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.011  cat              132085 132082   0 /usr/bin/cat /proc/2240539/stat\n17.012  cat              132086 132082   0 /usr/bin/cat /proc/4193716/stat\n17.014  sleep            132087 132082   0 /usr/bin/sleep 1\n17.024  rustc            132091 131836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"proptest\", \"proptest1\", \"serde\", \"serde1\")) -C metadata=96b42ddf4b1fc252 ...\n17.029  rustc            132092 131676   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.037  rustc            132092 131676   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.044  rustc            132109 131892   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.052  rustc            132110 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name url --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/url-2.5.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"std\" ...\n17.055  docker           132123 131676   0 /usr/bin/docker --help\n17.056  rustc            132109 131892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.071  docker           132144 131892   0 /usr/bin/docker --help\n17.077  docker           132150 131676   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.100  runc             132166 1599     0 /usr/bin/runc --version\n17.100  docker           132167 131892   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.107  docker-init      132177 1599     0 /usr/bin/docker-init --version\n17.110  docker           132179 131676   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.119  runc             132188 1599     0 /usr/bin/runc --version\n17.123  docker-init      132199 1599     0 /usr/bin/docker-init --version\n17.126  docker           132201 131892   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.131  runc             132207 1599     0 /usr/bin/runc --version\n17.137  docker-init      132212 1599     0 /usr/bin/docker-init --version\n17.150  runc             132224 1599     0 /usr/bin/runc --version\n17.157  docker-init      132232 1599     0 /usr/bin/docker-init --version\n17.176  rustup           132244 131676   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.188  rustup           132266 131676   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.196  rustup           132281 131892   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.206  rustup           132299 131892   0 \n17.228  rustup           132328 131676   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.234  cc               132329 132091   0 /tmp/native-trace-130598-1783993028240/shims/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustciBA1fO/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.1tmmm16.rcgu.o ...\n17.236  cc               132338 132329   0 /usr/bin/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustciBA1fO/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.1tmmm16.rcgu.o ...\n17.242  collect2         132339 132338   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJgUY10.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.245  ld.lld           132340 132339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJgUY10.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791 ...\n17.250  rust-lld         132340 132339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJgUY10.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.252  rustup           132341 131892   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.260  uname            132350 131676   0 /usr/bin/uname -r\n17.282  docker           132367 131676   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.284  uname            132368 131892   0 /usr/bin/uname -r\n17.305  docker           132378 131892   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.323  systemd-sysctl   132390 130415   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfe700e9 --prefix=/net/ipv4/neigh/vethfe700e9 --prefix=/net/ipv6/conf/vethfe700e9 --prefix=/net/ipv6/neigh/vethfe700e9\n17.324  systemd-sysctl   132389 130420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0dfb9a9 --prefix=/net/ipv4/neigh/veth0dfb9a9 --prefix=/net/ipv6/conf/veth0dfb9a9 --prefix=/net/ipv6/neigh/veth0dfb9a9\n17.330  build-script-bu  132392 131836   0 /target/debug/build/camino-2e1d3896195e9791/build-script-build\n17.332  rustc            132393 132392   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n17.347  containerd-shim  132397 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597ad42a0 start\n17.348  rustc            132396 131836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name camino --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"proptest\", \"proptest1\", \"serde\", \"serde1\")) -C metadata=5b90b5cf8b9b56db ...\n17.351  containerd-shim  132404 132397   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597ad42a0 -address /var/run/docker/containerd/containerd.sock\n17.357  runc             132418 132404   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597a cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597ad42a0\n17.357  systemd-sysctl   132419 130415   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3e44cd6 --prefix=/net/ipv4/neigh/veth3e44cd6 --prefix=/net/ipv6/conf/veth3e44cd6 --prefix=/net/ipv6/neigh/veth3e44cd6\n17.359  systemd-sysctl   132420 130420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetheac6055 --prefix=/net/ipv4/neigh/vetheac6055 --prefix=/net/ipv6/conf/vetheac6055 --prefix=/net/ipv6/neigh/vetheac6055\n17.366  exe              132431 132418   0 /proc/self/exe init\n17.384  containerd-shim  132439 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d9eba0 start\n17.387  containerd-shim  132446 132439   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d9eba0 -address /var/run/docker/containerd/containerd.sock\n17.393  runc             132456 132446   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d9eba0\n17.399  exe              132463 132456   0 /proc/self/exe init\n17.403  exe              132467 132418   0 /proc/1599/exe -exec-root=/var/run/docker cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597ad42a0 d7da31e8f8e1\n17.426  exe              132482 1599     0 /proc/self/exe /var/run/docker/netns/82a5db342b7c all false\n17.436  exe              132491 132456   0 /proc/1599/exe -exec-root=/var/run/docker dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d9eba0 d7da31e8f8e1\n17.460  exe              132507 1599     0 /proc/self/exe /var/run/docker/netns/fb38386d6db0 all false\n17.461  rustc            132506 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name http_types --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-std\" --cfg feature=\"cookie\" --cfg feature=\"cookie-secure\" ...\n17.476  runc             132521 132404   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597a --log-format json --systemd-cgroup start cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597ad42a0\n17.486  sh               132433 132404   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.487  cargo            132531 132433   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.500  cargo-native-tr  132531 132433   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.505  cargo            132533 132531   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.518  runc             132536 132446   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d --log-format json --systemd-cgroup start dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d9eba0\n17.523  rustc            132542 132533   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.530  sh               132475 132446   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.531  rustc            132548 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name http_types --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-std\" --cfg feature=\"cookie\" --cfg feature=\"cookie-secure\" ...\n17.534  cargo            132550 132475   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n17.545  rustc            132553 132533   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.552  cargo-native-tr  132550 132475   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.560  cargo            132563 132550   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.581  rustc            132570 132563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.600  rustc            132573 132563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.610  execsnoop        132575 132531   0 /usr/local/bin/execsnoop -t\n17.612  python3          132575 132531   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.664  execsnoop        132615 132550   0 /usr/local/bin/execsnoop -t\n17.665  python3          132615 132550   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.016  sed              132850 132082   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.019  cat              132853 132082   0 /usr/bin/cat /proc/2240539/stat\n18.022  cat              132857 132082   0 /usr/bin/cat /proc/4193716/stat\n18.468  runc             132901 124362   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d --log-format json --systemd-cgroup kill --all 59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d598bd 9\n18.485  runc             132907 124362   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d --log-format json --systemd-cgroup delete 59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d598bd\n18.676  containerd-shim  132919 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d598bd -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d delete\n18.679  runc             132926 132919   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d598b --log-format json delete --force 59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d598bd\n18.711  systemd-sysctl   132935 130420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc57fa1f --prefix=/net/ipv4/neigh/vethc57fa1f --prefix=/net/ipv6/conf/vethc57fa1f --prefix=/net/ipv6/neigh/vethc57fa1f\n"
}
```

#### Record 17

```json
{
  "argv": [
    "/target/debug/build/smartstring-82c922e517a55c78/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 127365,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/smartstring-82c922e517a55c78/build-script-build",
  "pid": 127365,
  "ppid": 126571,
  "root_cargo_pid": 126571,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
  "build_script_root_pid": 127365,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 127367,
  "ppid": 127365,
  "root_cargo_pid": 126571,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_build_script_out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 19

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_bfa3973c41545b27_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/smartstring-0a3a76266f542231/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 127365,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 127397,
  "ppid": 127365,
  "root_cargo_pid": 126571,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_build_script_out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
  "build_script_root_pid": 127365,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 127416,
  "ppid": 127365,
  "root_cargo_pid": 126571,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_build_script_out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 21

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_bfa3973c41545b27_1",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/smartstring-0a3a76266f542231/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 127365,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 127426,
  "ppid": 127365,
  "root_cargo_pid": 126571,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_build_script_out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 22

```json
{
  "crate": "smartstring",
  "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "event_id": "bsrun:668863cf82af4238:736d8391d94ae7d6:4bd9bf900cb310d9",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/smartstring-82c922e517a55c78/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
  "out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
  "success": true,
  "target": null,
  "version": "1.0.1",
  "_owner": {
    "crate": "smartstring",
    "version": "1.0.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
    "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
  "build_script_root_pid": 127365,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 127367,
  "ppid": 127365,
  "root_cargo_pid": 126571,
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
    "autocfg_bfa3973c41545b27_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/smartstring-0a3a76266f542231/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 127365,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 127397,
  "ppid": 127365,
  "root_cargo_pid": 126571,
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
  "build_script_root_pid": 127365,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 127416,
  "ppid": 127365,
  "root_cargo_pid": 126571,
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
    "autocfg_bfa3973c41545b27_1",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/smartstring-0a3a76266f542231/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 127365,
  "build_script_target_dir": "smartstring-82c922e517a55c78",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 127426,
  "ppid": 127365,
  "root_cargo_pid": 126571,
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
  "time": "2026-07-14T01:37:15.684750+00:00",
  "crate": "smartstring",
  "version": "1.0.1",
  "architecture": "riscv64",
  "duration_seconds": 31.677091705147177,
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
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "manifest_path": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "workspace_root": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1"
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
          "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
          "name": "smartstring",
          "version": "1.0.1",
          "manifest_path": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1"
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
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 127258,
      "ppid": 127226,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "event_id": "used:cc:22dbc809832df36d:ec6ebbd7e4ff9d1c:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
      "pid": 127258,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "event_id": "used:cc:22dbc809832df36d:1fd6a2a55b1e0e64:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
      "pid": 127258,
      "sha256": "2fa666dc91f31bcc9ecbf9b79b035b7a2cc61d2135563ffd9b25da9568bd9827",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "event_id": "used:cc:22dbc809832df36d:90f1fa63469f029b:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
      "pid": 127258,
      "sha256": "22f1d122c0407a66d79343639c6a5859bc8b8cd5b8199044b270ce1a5ee27de5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "event_id": "used:cc:22dbc809832df36d:71563c95771de99c:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
      "pid": 127258,
      "sha256": "aab45017d78caf1d5a5dfc404fb71a93139be5b9c855808cfc39d435faa5ceb8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "event_id": "used:cc:22dbc809832df36d:7c6714830c1a9177:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
      "pid": 127258,
      "sha256": "0824212ea377725cbeb9b08ae84b54ec3057ac4fcfb138e77834ebde058ee084",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "event_id": "used:cc:22dbc809832df36d:cee1fe5052e40018:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
      "pid": 127258,
      "sha256": "3b92a3ed1da4a2386e4689b63d2419f4635a64eed61c9a5f80c76d337bca3cfd",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "event_id": "used:cc:22dbc809832df36d:f22bf095004ccac0:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
      "pid": 127258,
      "sha256": "939af0360a8c0b8810710e9d8406239b01463a08796c8dd9f9b39fd96876275d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "event_id": "used:cc:22dbc809832df36d:86771fb08a28c15f:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
      "pid": 127258,
      "sha256": "4e31e1b0e99890fd6b74d4e97d346c63686d04aa5adcfe5b041fcb571ec4738f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "event_id": "used:cc:22dbc809832df36d:15bca158cf83f5f8:e2b4f7e6daceb981",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78",
      "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
      "pid": 127258,
      "sha256": "62de7ab46fb0e396187e070f791310c1e5ca15bbe27ca62a0fd7ec8de454e324",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "cargo_pkg_name": "smartstring",
      "cargo_pkg_version": "1.0.1",
      "context_path": "/tmp/native-trace-124567-1783993011081/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-124567-1783993011081/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 127258,
      "ppid": 127226,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
        "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3",
        "/target/debug/build/smartstring-82c922e517a55c78",
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
          "directory": "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/rustcyxDMc3/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.04fdtgeundmlebniuxyrnlnb3.1dcep9o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.1dlbphqk4pveiqn043fim7koz.1dcep9o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.3yxc5sq3ptbmpyiizi8kycs6g.1dcep9o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.440ykrx74tx7w9i7cstod39a2.1dcep9o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.6ijk3niq1vxkwoq9j3h6xnun1.1dcep9o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bkw4ms8d2kqwjdjqq3q4xkieq.1dcep9o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.cfroy69usz078p95hd2z77sw5.1dcep9o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/smartstring-82c922e517a55c78",
          "kind": "object",
          "path": "/target/debug/build/smartstring-82c922e517a55c78/build_script_build-82c922e517a55c78.bhsrzp0z6067rmsx76sd3gc49.1dcep9o.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-127258-1783993017266255748.map",
      "pid": 127258,
      "ppid": 127226,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-127258-1783993017266255748.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
      "parsed_event_count": 902,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 904,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": ".69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4e81e20256362857 ...\n13.959  runc             131360 121759   0 \n13.976  rustc            131374 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name yoke --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yoke-0.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n13.996  rustc            131384 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerovec --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerovec-0.11.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.003  rustc            131388 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerotrie --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerotrie-0.2.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.111  rustc            131402 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.113  rustc            131403 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.124  rustc            131409 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerovec --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerovec-0.11.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.126  rustc            131410 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name zerotrie --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zerotrie-0.2.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.165  containerd-shim  131425 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 785747dfac080db39516e6a9929e61ce4a3f2cb792a5a96f5d4af5076e54195d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785747dfac080db39516e6a9929e61ce4a3f2cb792a5a96f5d4af5076e5 delete\n14.170  runc             131432 131425   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/785747dfac080db39516e6a9929e61ce4a3f2cb792a5a96f5d4af5076e54195 --log-format json delete --force 785747dfac080db39516e6a9929e61ce4a3f2cb792a5a96f5d4af5076e54195d\n14.187  rustc            131439 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n14.222  systemd-sysctl   131446 130420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4cb96b --prefix=/net/ipv4/neigh/vethf4cb96b --prefix=/net/ipv6/conf/vethf4cb96b --prefix=/net/ipv6/neigh/vethf4cb96b\n14.476  git              131466 2235138   0 /usr/bin/git config --get commit.template\n14.496  git              131467 2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n14.516  git              131473 2235138   0 /usr/bin/git status -z -uall\n14.539  git              131475 2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n14.553  rustc            131483 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tinystr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinystr-0.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.562  rustc            131484 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name potential_utf --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/potential_utf-0.1.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.650  rustc            131502 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_collections --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_collections-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.713  rustc            131520 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tinystr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinystr-0.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.714  rustc            131518 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_urlencoded --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_urlencoded-0.7.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=78a0ef8aa432b300 ...\n14.714  rustc            131519 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_qs --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_qs-0.8.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"actix\", \"actix-web\", \"actix-web2\", \"actix2\", \"default\", \"futures\", \"tracing\", \"warp\", \"warp-framework\")) ...\n14.726  rustc            131517 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name potential_utf --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/potential_utf-0.1.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.726  rustc            131525 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_locale_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_locale_core-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.810  rustc            131549 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_collections --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_collections-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n14.861  rustc            131559 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_locale_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_locale_core-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.105  16               131585 1        0 /proc/self/fd/16 --deserialize 147 --log-level info --log-target journal-or-kmsg\n15.111  16               131587 1        0 /proc/self/fd/16 --deserialize 161 --log-level info --log-target journal-or-kmsg\n15.254  rustc            131608 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna_adapter --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna_adapter-1.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"compiled_data\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiled_data\")) ...\n15.291  cc               131612 129959   0 /tmp/native-trace-119488-1783992999210/shims/cc -Wl,--version-script=/target/debug/deps/rustc89Iqr2/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc89Iqr2/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n15.297  cc               131617 131612   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc89Iqr2/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc89Iqr2/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n15.307  collect2         131620 131617   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDngMYh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc89Iqr2/raw-dylibs ...\n15.309  ld.lld           131621 131620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDngMYh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc89Iqr2/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.316  rust-lld         131621 131620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDngMYh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n15.343  rustc            131625 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"compiled_data\" --cfg feature=\"std\" ...\n15.354  systemd-coredum  131585 1        0 /usr/lib/systemd/systemd-coredump\n15.356  drkonqi-coredum  131587 1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 901-131583-0\n15.411  cc               131647 130034   0 /tmp/native-trace-119438-1783992999031/shims/cc -Wl,--version-script=/target/debug/deps/rustcUMVHHm/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcUMVHHm/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n15.413  cc               131648 131647   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcUMVHHm/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcUMVHHm/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n15.417  collect2         131649 131648   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Ir7KP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcUMVHHm/raw-dylibs ...\n15.418  ld.lld           131650 131649   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Ir7KP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcUMVHHm/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.421  rust-lld         131650 131649   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc6Ir7KP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.517  cross            131676 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.519  rustc            131679 131676   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.525  rustc            131679 131676   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.537  rustc            131693 131676   0 /home/xmoe/.cargo/bin/rustc -vV\n15.538  rustc            131690 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n15.544  rustc            131693 131676   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.554  cargo            131706 131676   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.560  cargo            131706 131676   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.571  rustc            131715 131706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.583  rustc            131721 131706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.585  rustc            131720 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name url --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/url-2.5.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"std\" ...\n15.596  rustc            131734 131706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.601  rustc            131730 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.605  rustc            131735 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n15.621  rustc            131745 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.808  abrt-server      131779 1118     0 /usr/bin/abrt-server -s\n15.810  9                131780 4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n15.828  drkonqi-coredum  131780 4003047   0 /usr/libexec/drkonqi-coredump-launcher\n15.835  abrt-handle-eve  131781 131779   0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:37:11.649421-121589\n15.853  sh               131788 131781   0 /bin/sh -c abrt-action-save-package-data\\n\n15.855  rustc            131786 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.855  rustc            131787 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.856  abrt-action-sav  131788 131781   0 /usr/bin/abrt-action-save-package-data\n15.875  rustc            131804 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_properties --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_properties-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.879  rustc            131805 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_normalizer --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_normalizer-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n15.913  runc             131813 121618   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed --log-format json --systemd-cgroup kill --all c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed10eeb 9\n15.931  runc             131819 121618   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed --log-format json --systemd-cgroup delete c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed10eeb\n15.934  sh               131824 131781   0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n15.939  cat              131827 131825   0 /usr/bin/cat uid\n15.939  cut              131826 131824   0 /usr/bin/cut -d: -f1\n15.943  getent           131825 131824   0 /usr/bin/getent passwd 1000\n15.947  lscpu            131828 131824   0 /usr/bin/lscpu\n15.966  sh               131829 131781   0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n15.968  runlevel         131830 131829   0 /usr/bin/runlevel\n15.984  sh               131831 131781   0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n15.986  grep             131832 131831   0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n15.989  grep             131833 131831   0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n15.992  grep             131834 131831   0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n15.995  abrt-action-cor  131835 131831   0 /usr/libexec/abrt-action-coredump -x\n16.043  cargo            131836 130598   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n16.058  rustc            131842 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_urlencoded --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_urlencoded-0.7.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=7bdfecc0fabf6ec6 ...\n16.058  rustc            131841 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_qs --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_qs-0.8.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"actix\", \"actix-web\", \"actix-web2\", \"actix2\", \"default\", \"futures\", \"tracing\", \"warp\", \"warp-framework\")) ...\n16.062  rustc            131843 131836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.090  abrt-action-gen  131854 131831   0 /usr/bin/abrt-action-generate-core-backtrace\n16.115  rustc            131858 119869   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name http_types --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-std\" --cfg feature=\"cookie\" --cfg feature=\"cookie-secure\" ...\n16.132  rustc            131863 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_urlencoded --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_urlencoded-0.7.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=04dc41fade5f6b3d ...\n16.135  rustc            131865 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde_qs --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_qs-0.8.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"actix\", \"actix-web\", \"actix-web2\", \"actix2\", \"default\", \"futures\", \"tracing\", \"warp\", \"warp-framework\")) ...\n16.139  containerd-shim  131873 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed10eeb -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed delete\n16.144  runc             131883 131873   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed10ee --log-format json delete --force c35b58abe64f68b56aefbead27d88e85cbe15b9f3fa980d8114b9b5d0ed10eeb\n16.155  cross            131892 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n16.157  rustc            131894 131892   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.169  rustc            131894 131892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.172  abrt-action-ana  131907 131831   0 /usr/bin/abrt-action-analyze-vulnerability\n16.176  eu-readelf       131909 131908   0 /usr/bin/eu-readelf -n coredump\n16.176  grep             131910 131908   0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n16.178  sed              131911 131908   0 /usr/bin/sed s/[^0-9]//g\n16.200  gdb              131921 131913   0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n16.204  rustc            131923 131892   0 /home/xmoe/.cargo/bin/rustc -vV\n16.214  rustc            131923 131892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.215  sh               131932 130420   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth32e8199\n16.217  sed              131936 131932   0 /usr/bin/sed -n s/^driver: //p\n16.218  ethtool          131935 131932   0 /usr/sbin/ethtool -i veth32e8199\n16.237  systemd-sysctl   131941 130420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth32e8199 --prefix=/net/ipv4/neigh/veth32e8199 --prefix=/net/ipv6/conf/veth32e8199 --prefix=/net/ipv6/neigh/veth32e8199\n16.241  iconv            131943 131921   0 /usr/bin/iconv -l\n16.256  cargo            131955 131892   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.265  cargo            131955 131892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.303  rustc            131969 131955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.316  rustc            131974 131955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.332  rustc            131978 131955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.334  rustup           131979 120100   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.385  abrt-action-ana  131994 131831   0 /usr/bin/abrt-action-analyze-c\n16.397  eu-unstrip       131995 131994   0 /usr/bin/eu-unstrip --core=./coredump -n\n16.415  abrt-action-lis  131996 131831   0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n16.472  cat              132002 132001   0 /usr/bin/cat executable\n16.474  cat              132005 132001   0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:37:11.649421-121589/uid\n16.475  journalctl       132006 132001   0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n16.488  abrt-action-cor  132008 131831   0 /usr/libexec/abrt-action-coredump -r\n16.552  abrt-handle-eve  132014 131779   0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.567  sh               132016 132014   0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n16.569  dbus-send        132016 132014   0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.572  sh               132017 132014   0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n16.574  abrt-action-not  132018 132017   0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.634  16               132020 1        0 /proc/self/fd/16 --deserialize 137 --log-level info --log-target journal-or-kmsg\n16.648  abrt-dbus        132020 1        0 /usr/sbin/abrt-dbus -t133\n16.690  sh               132025 132018   0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n16.692  reporter-system  132025 132018   0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n16.747  rustc            132031 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna_adapter --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna_adapter-1.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"compiled_data\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiled_data\")) ...\n16.785  rustc            132042 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna_adapter --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna_adapter-1.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"compiled_data\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiled_data\")) ...\n16.786  rustc            132046 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"compiled_data\" --cfg feature=\"std\" ...\n16.838  rustc            132061 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"compiled_data\" --cfg feature=\"std\" ...\n16.924  rustc            132067 131706   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.959  rustc            132069 131955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.972  sh               132074 2147557   0 /bin/sh -c which ps\n16.973  which            132074 2147557   0 /usr/bin/which ps\n16.976  sh               132076 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.977  rustc            132075 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name url --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/url-2.5.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"std\" ...\n16.979  ps               132076 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.004  sh               132082 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.006  cpuUsage.sh      132082 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.008  sed              132084 132082   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.011  cat              132085 132082   0 /usr/bin/cat /proc/2240539/stat\n17.012  cat              132086 132082   0 /usr/bin/cat /proc/4193716/stat\n17.014  sleep            132087 132082   0 /usr/bin/sleep 1\n17.024  rustc            132091 131836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"proptest\", \"proptest1\", \"serde\", \"serde1\")) -C metadata=96b42ddf4b1fc252 ...\n17.029  rustc            132092 131676   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.037  rustc            132092 131676   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.044  rustc            132109 131892   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.052  rustc            132110 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name url --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/url-2.5.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"serde\" --cfg feature=\"std\" ...\n17.055  docker           132123 131676   0 /usr/bin/docker --help\n17.056  rustc            132109 131892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.071  docker           132144 131892   0 /usr/bin/docker --help\n17.077  docker           132150 131676   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.100  runc             132166 1599     0 /usr/bin/runc --version\n17.100  docker           132167 131892   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.107  docker-init      132177 1599     0 /usr/bin/docker-init --version\n17.110  docker           132179 131676   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.119  runc             132188 1599     0 /usr/bin/runc --version\n17.123  docker-init      132199 1599     0 /usr/bin/docker-init --version\n17.126  docker           132201 131892   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.131  runc             132207 1599     0 /usr/bin/runc --version\n17.137  docker-init      132212 1599     0 /usr/bin/docker-init --version\n17.150  runc             132224 1599     0 /usr/bin/runc --version\n17.157  docker-init      132232 1599     0 /usr/bin/docker-init --version\n17.176  rustup           132244 131676   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.188  rustup           132266 131676   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.196  rustup           132281 131892   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.206  rustup           132299 131892   0 \n17.228  rustup           132328 131676   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.234  cc               132329 132091   0 /tmp/native-trace-130598-1783993028240/shims/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustciBA1fO/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.1tmmm16.rcgu.o ...\n17.236  cc               132338 132329   0 /usr/bin/cc -m64 /target/debug/build/camino-2e1d3896195e9791/rustciBA1fO/symbols.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.00lkd36uboh4jr4ugfs1so7n6.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.06bdc1vm5cmyg0hdzifux6mr8.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.08l1664031v0dc78znv2mdstx.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0ml3cfgoqiovjdpl3imyx8xv0.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.0y2qv513v9nxnvc1i6q4szlbm.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.119o3hiyv3q0thv6k0pln7yj0.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.16v0gswcy344qi1tpr6x9961n.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1d47cqd6ykvcue5zvq7izob0y.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.1xsulyfrtjnkihqwje1bljt7e.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.20ajzft8x55uttpxuc1y7v9c8.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.2d4xhhhpgpazhgmua7fdvwnz4.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3kin9vbf2isky6x5vilgvbofe.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3lw352t8tkwh746bm1sphpjgg.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3rlh3kx1y9yxj08gpp4wwl765.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.3u2v0459bzlbhej62nsvozcl2.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.4170ipnl7m245z3uexshl7rxc.1tmmm16.rcgu.o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791.46c09k4iv2uy3kn6dhuew8vis.1tmmm16.rcgu.o ...\n17.242  collect2         132339 132338   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJgUY10.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.245  ld.lld           132340 132339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJgUY10.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/camino-2e1d3896195e9791/build_script_build-2e1d3896195e9791 ...\n17.250  rust-lld         132340 132339   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJgUY10.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.252  rustup           132341 131892   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.260  uname            132350 131676   0 /usr/bin/uname -r\n17.282  docker           132367 131676   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.284  uname            132368 131892   0 /usr/bin/uname -r\n17.305  docker           132378 131892   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.323  systemd-sysctl   132390 130415   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfe700e9 --prefix=/net/ipv4/neigh/vethfe700e9 --prefix=/net/ipv6/conf/vethfe700e9 --prefix=/net/ipv6/neigh/vethfe700e9\n17.324  systemd-sysctl   132389 130420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0dfb9a9 --prefix=/net/ipv4/neigh/veth0dfb9a9 --prefix=/net/ipv6/conf/veth0dfb9a9 --prefix=/net/ipv6/neigh/veth0dfb9a9\n17.330  build-script-bu  132392 131836   0 /target/debug/build/camino-2e1d3896195e9791/build-script-build\n17.332  rustc            132393 132392   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n17.347  containerd-shim  132397 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597ad42a0 start\n17.348  rustc            132396 131836   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name camino --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"proptest\", \"proptest1\", \"serde\", \"serde1\")) -C metadata=5b90b5cf8b9b56db ...\n17.351  containerd-shim  132404 132397   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597ad42a0 -address /var/run/docker/containerd/containerd.sock\n17.357  runc             132418 132404   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597a cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597ad42a0\n17.357  systemd-sysctl   132419 130415   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3e44cd6 --prefix=/net/ipv4/neigh/veth3e44cd6 --prefix=/net/ipv6/conf/veth3e44cd6 --prefix=/net/ipv6/neigh/veth3e44cd6\n17.359  systemd-sysctl   132420 130420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetheac6055 --prefix=/net/ipv4/neigh/vetheac6055 --prefix=/net/ipv6/conf/vetheac6055 --prefix=/net/ipv6/neigh/vetheac6055\n17.366  exe              132431 132418   0 /proc/self/exe init\n17.384  containerd-shim  132439 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d9eba0 start\n17.387  containerd-shim  132446 132439   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d9eba0 -address /var/run/docker/containerd/containerd.sock\n17.393  runc             132456 132446   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d9eba0\n17.399  exe              132463 132456   0 /proc/self/exe init\n17.403  exe              132467 132418   0 /proc/1599/exe -exec-root=/var/run/docker cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597ad42a0 d7da31e8f8e1\n17.426  exe              132482 1599     0 /proc/self/exe /var/run/docker/netns/82a5db342b7c all false\n17.436  exe              132491 132456   0 /proc/1599/exe -exec-root=/var/run/docker dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d9eba0 d7da31e8f8e1\n17.460  exe              132507 1599     0 /proc/self/exe /var/run/docker/netns/fb38386d6db0 all false\n17.461  rustc            132506 120239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name http_types --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-std\" --cfg feature=\"cookie\" --cfg feature=\"cookie-secure\" ...\n17.476  runc             132521 132404   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597a --log-format json --systemd-cgroup start cb414b363ca0ab6501a7b20d91438cde810aa3794af955d33299dc7597ad42a0\n17.486  sh               132433 132404   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.487  cargo            132531 132433   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.500  cargo-native-tr  132531 132433   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.505  cargo            132533 132531   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.518  runc             132536 132446   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d --log-format json --systemd-cgroup start dd5d496460975d8f31e02b5909ecb9a7f826e0c8eb3e6b76d9fc46e329d9eba0\n17.523  rustc            132542 132533   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.530  sh               132475 132446   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.531  rustc            132548 120471   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name http_types --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-std\" --cfg feature=\"cookie\" --cfg feature=\"cookie-secure\" ...\n17.534  cargo            132550 132475   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n17.545  rustc            132553 132533   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.552  cargo-native-tr  132550 132475   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.560  cargo            132563 132550   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.581  rustc            132570 132563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.600  rustc            132573 132563   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.610  execsnoop        132575 132531   0 /usr/local/bin/execsnoop -t\n17.612  python3          132575 132531   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.664  execsnoop        132615 132550   0 /usr/local/bin/execsnoop -t\n17.665  python3          132615 132550   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n18.016  sed              132850 132082   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.019  cat              132853 132082   0 /usr/bin/cat /proc/2240539/stat\n18.022  cat              132857 132082   0 /usr/bin/cat /proc/4193716/stat\n18.468  runc             132901 124362   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d --log-format json --systemd-cgroup kill --all 59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d598bd 9\n18.485  runc             132907 124362   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d --log-format json --systemd-cgroup delete 59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d598bd\n18.676  containerd-shim  132919 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d598bd -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d delete\n18.679  runc             132926 132919   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d598b --log-format json delete --force 59be969c6d6b031e164b9c2b7bbb39c6f71557322a0cd10a33e905bf09d598bd\n18.711  systemd-sysctl   132935 130420   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc57fa1f --prefix=/net/ipv4/neigh/vethc57fa1f --prefix=/net/ipv6/conf/vethc57fa1f --prefix=/net/ipv6/neigh/vethc57fa1f\n"
    },
    {
      "argv": [
        "/target/debug/build/smartstring-82c922e517a55c78/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 127365,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/smartstring-82c922e517a55c78/build-script-build",
      "pid": 127365,
      "ppid": 126571,
      "root_cargo_pid": 126571,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 127365,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 127367,
      "ppid": 127365,
      "root_cargo_pid": 126571,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_bfa3973c41545b27_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/smartstring-0a3a76266f542231/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 127365,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 127397,
      "ppid": 127365,
      "root_cargo_pid": 126571,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 127365,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 127416,
      "ppid": 127365,
      "root_cargo_pid": 126571,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_bfa3973c41545b27_1",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/smartstring-0a3a76266f542231/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 127365,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 127426,
      "ppid": 127365,
      "root_cargo_pid": 126571,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "smartstring",
      "cwd": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "event_id": "bsrun:668863cf82af4238:736d8391d94ae7d6:4bd9bf900cb310d9",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/smartstring-82c922e517a55c78/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
      "out_dir": "/target/debug/build/smartstring-82c922e517a55c78/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
      "success": true,
      "target": null,
      "version": "1.0.1",
      "_owner": {
        "crate": "smartstring",
        "version": "1.0.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1#smartstring@1.0.1",
        "manifest_dir": "/tmp/crate-build-riscv64-m75oymyz/src/smartstring-1.0.1",
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
      "build_script_root_pid": 127365,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 127367,
      "ppid": 127365,
      "root_cargo_pid": 126571,
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
        "autocfg_bfa3973c41545b27_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/smartstring-0a3a76266f542231/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 127365,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 127397,
      "ppid": 127365,
      "root_cargo_pid": 126571,
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
      "build_script_root_pid": 127365,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 127416,
      "ppid": 127365,
      "root_cargo_pid": 126571,
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
        "autocfg_bfa3973c41545b27_1",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/smartstring-0a3a76266f542231/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 127365,
      "build_script_target_dir": "smartstring-82c922e517a55c78",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 127426,
      "ppid": 127365,
      "root_cargo_pid": 126571,
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
