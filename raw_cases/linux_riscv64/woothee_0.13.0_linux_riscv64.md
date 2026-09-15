# `woothee` `0.13.0`

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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
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
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5",
    "/target/debug/build/woothee-de9e3cc5c3579e7b",
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
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-426752-1783994425748725622.map",
  "pid": 426752,
  "ppid": 426727,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-426752-1783994425748725622.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "workspace_root": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@0.5.3",
      "name": "aho-corasick",
      "version": "0.5.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.5.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.5.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
      "name": "aho-corasick",
      "version": "1.1.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
      "name": "autocfg",
      "version": "1.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-set@0.5.3",
      "name": "bit-set",
      "version": "0.5.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.5.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.5.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-vec@0.6.3",
      "name": "bit-vec",
      "version": "0.6.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.6.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.6.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#convert_case@0.4.0",
      "name": "convert_case",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/convert_case-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/convert_case-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#derive_more@0.99.20",
      "name": "derive_more",
      "version": "0.99.20",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_more-0.99.20/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_more-0.99.20"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fancy-regex@0.3.5",
      "name": "fancy-regex",
      "version": "0.3.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.3.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.3.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.12.3",
      "name": "hashbrown",
      "version": "0.12.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@1.9.3",
      "name": "indexmap",
      "version": "1.9.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-1.9.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-1.9.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#kernel32-sys@0.2.2",
      "name": "kernel32-sys",
      "version": "0.2.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/kernel32-sys-0.2.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/kernel32-sys-0.2.2"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#linked-hash-map@0.5.6",
      "name": "linked-hash-map",
      "version": "0.5.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linked-hash-map-0.5.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linked-hash-map-0.5.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@0.1.11",
      "name": "memchr",
      "version": "0.1.11",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-0.1.11/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-0.1.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
      "name": "memchr",
      "version": "2.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
      "name": "proc-macro2",
      "version": "1.0.106",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
      "name": "quote",
      "version": "1.0.46",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@0.1.80",
      "name": "regex",
      "version": "0.1.80",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-0.1.80/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-0.1.80"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.3.9",
      "name": "regex-syntax",
      "version": "0.3.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.3.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.3.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
      "name": "regex-syntax",
      "version": "0.8.11",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc_version@0.4.1",
      "name": "rustc_version",
      "version": "0.4.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc_version-0.4.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc_version-0.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
      "name": "ryu",
      "version": "1.0.23",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#semver@1.0.28",
      "name": "semver",
      "version": "1.0.28",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.28/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.28"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
      "name": "serde",
      "version": "1.0.228",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_yaml@0.8.26",
      "name": "serde_yaml",
      "version": "0.8.26",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_yaml-0.8.26/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_yaml-0.8.26"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
      "name": "syn",
      "version": "2.0.118",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#thread-id@2.0.0",
      "name": "thread-id",
      "version": "2.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread-id-2.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread-id-2.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#thread_local@0.2.7",
      "name": "thread_local",
      "version": "0.2.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-0.2.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-0.2.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#uap-rust@0.0.4",
      "name": "uap-rust",
      "version": "0.0.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uap-rust-0.0.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uap-rust-0.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#uaparser@0.4.0",
      "name": "uaparser",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uaparser-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uaparser-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
      "name": "unicode-ident",
      "version": "1.0.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#utf8-ranges@0.1.3",
      "name": "utf8-ranges",
      "version": "0.1.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/utf8-ranges-0.1.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/utf8-ranges-0.1.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.2.8",
      "name": "winapi",
      "version": "0.2.8",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.2.8/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.2.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-build@0.1.1",
      "name": "winapi-build",
      "version": "0.1.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-build-0.1.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-build-0.1.1"
    },
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
      "name": "woothee",
      "version": "0.13.0",
      "manifest_path": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#yaml-rust@0.3.5",
      "name": "yaml-rust",
      "version": "0.3.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.3.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.3.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#yaml-rust@0.4.5",
      "name": "yaml-rust",
      "version": "0.4.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.4.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.4.5"
    }
  ],
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 426752,
  "ppid": 426727,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "woothee",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "event_id": "used:cc:bd63174f748c2f6e:d8f51a27739a5660:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
  "pid": 426752,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "woothee",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "event_id": "used:cc:bd63174f748c2f6e:2c0c507687cb6078:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
  "pid": 426752,
  "sha256": "4117007a265181226cd649365b3d8ae1d6e250bd1c163fa93b4aaf35f8e5dd4f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "woothee",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "event_id": "used:cc:bd63174f748c2f6e:e848e7213a41b227:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
  "pid": 426752,
  "sha256": "eb140e94e6896f3798bcb62570ca2b1d2c246c64a50afb8570417363c3541cdc",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "woothee",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "event_id": "used:cc:bd63174f748c2f6e:0707bd8802db9734:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
  "pid": 426752,
  "sha256": "3f25d8a6622c8e7e286f9de641bfcbc79dcacb80ded6d9ea2bcd5c6808e3ad3e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "woothee",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "event_id": "used:cc:bd63174f748c2f6e:20c9858ac8bb582e:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
  "pid": 426752,
  "sha256": "bee848b3af42122546b3958d202b5357d08c60f7cc660f3c623098b90baa381a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "woothee",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "event_id": "used:cc:bd63174f748c2f6e:abb4b8088885daab:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
  "pid": 426752,
  "sha256": "d0516df22cc030b9fe63b73240a995c7a33147b153983b3aa576846c13fa5d50",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "woothee",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "event_id": "used:cc:bd63174f748c2f6e:8c6b936929f3828d:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
  "pid": 426752,
  "sha256": "b52374f6cbdb3a7477835154e7ef065d57ae9030b6c77b7f31c72e88c14f94cb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "woothee",
  "cargo_pkg_version": "0.13.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "event_id": "used:cc:bd63174f748c2f6e:4a03c93f0e94f225:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
  "pid": 426752,
  "sha256": "cf9550fcdd6750b8b002d63f481db80394aa13baeaca84880915d0d589ea755d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
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
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "cargo_pkg_name": "woothee",
  "cargo_pkg_version": "0.13.0",
  "context_path": "/tmp/native-trace-426059-1783994423018/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-426059-1783994423018/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 426752,
  "ppid": 426727,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5",
    "/target/debug/build/woothee-de9e3cc5c3579e7b",
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
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-426752-1783994425748725622.map",
  "pid": 426752,
  "ppid": 426727,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-426752-1783994425748725622.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
  "parsed_event_count": 3979,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 3981,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": ".o\n20.130  sed              437623 437611   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.131  rustc            437627 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n20.131  rustc            437643 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"bytemuck\", \"example_generated\", \"serde\", \"serde_core\", \"std\")) ...\n20.135  aarch64-linux-g  437654 437653   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections -fdata-sections ...\n20.138  cc1              437655 437654   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.139  as               437656 437654   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.139  cat              437657 435544   0 /usr/bin/cat confdefs.h -\n20.141  rm               437658 435544   0 /usr/bin/rm -f conftest.o\n20.155  rustc            437640 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=cc8f9a7b2578854f ...\n20.165  powerpc64le-lin  437661 437659   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.169  cc1              437671 437661   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.175  rm               437678 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.209  cat              437681 430480   0 /usr/bin/cat confdefs.h -\n20.218  rm               437691 430480   0 /usr/bin/rm -f conftest.o conftest\n20.225  aarch64-linux-g  437696 437693   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections ...\n20.229  cc1              437698 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.229  as               437700 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/cc93U75G.o\n20.255  rustc            437644 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.256  rustc            437703 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n20.259  riscv64-linux-g  437652 437650   0 /usr/bin/riscv64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 -ffunction-sections ...\n20.259  rustc            437637 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.69.5/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"logging\" --cfg feature=\"prettyplease\" ...\n20.263  cc1              437706 437652   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.263  rustc            437704 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0919eec9d4c8c0c2 ...\n20.273  rustc            437711 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name linux_raw_sys --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(target_arch, values(\"xtensa\")) --cfg feature=\"elf\" --cfg ...\n20.275  rustc            437710 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.279  rustc            437705 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6cee1ea7c2ce8c63 ...\n20.282  cc               437714 437639   0 /tmp/native-trace-434802-1783994440811/shims/cc -m64 /target/debug/build/prettyplease-405734db8e85c51b/rustcECAZCe/symbols.o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.build_script_build.aaea0e150cf5cfc8-cgu.0. /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.8kx98gngi2nebs6p1mjm4mvsb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.288  rustc            437717 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libloading --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(libloading_docs) --check-cfg cfg(target_os, values(\"cygwin\")) --check-cfg ...\n20.289  rustc            437707 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) ...\n20.296  cc               437720 437714   0 /usr/bin/cc -m64 /target/debug/build/prettyplease-405734db8e85c51b/rustcECAZCe/symbols.o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.build_script_build.aaea0e150cf5cfc8-cgu.0. /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.8kx98gngi2nebs6p1mjm4mvsb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.298  as               437708 437652   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o conftest.o\n20.308  collect2         437724 437720   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.309  rm               437728 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.311  as               437673 437661   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.320  collect2         437735 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctI8CuH.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.322  ld               437737 437735   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctI8CuH.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.326  rm               437738 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.329  rustc            437716 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"std\" --cfg ...\n20.331  cat              437729 430490   0 /usr/bin/cat confdefs.h -\n20.334  rm               437742 430490   0 /usr/bin/rm -f conftest.o conftest\n20.340  sed              437752 437750   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.346  cat              437743 435544   0 /usr/bin/cat\n20.346  riscv64-linux-g  437748 437747   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.350  sed              437759 437758   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.355  cat              437763 435544   0 /usr/bin/cat confdefs.h -\n20.359  rm               437764 435544   0 /usr/bin/rm -f conftest.o\n20.362  powerpc64le-lin  437766 437765   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.365  cc1              437768 437766   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.367  as               437769 437766   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.374  ld.lld           437741 437724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b ...\n20.385  rustc            437770 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazycell --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"clippy\", \"nightly\", \"nightly-testing\", \"serde\")) -C metadata=4ad32744f67d8797 ...\n20.386  cc1              437760 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.389  as               437773 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccBIY51N.o\n20.390  rm               437772 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.391  rust-lld         437741 437724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.431  rm               437774 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.435  cat              437787 430480   0 /usr/bin/cat confdefs.h -\n20.440  rm               437788 430480   0 /usr/bin/rm -f conftest.o\n20.445  aarch64-linux-g  437791 437790   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC ...\n20.446  cc1              437792 437791   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.475  collect2         437785 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJ37tgL.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.479  ld               437796 437785   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJ37tgL.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.480  rm               437797 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.481  as               437793 437791   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.487  sed              437804 437803   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.504  cat              437799 435544   0 /usr/bin/cat\n20.507  rm               437806 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.509  sed              437810 437809   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.509  cat              437811 430480   0 /usr/bin/cat confdefs.h -\n20.512  rm               437812 430480   0 /usr/bin/rm -f conftest.o conftest\n20.521  cat              437816 435544   0 /usr/bin/cat confdefs.h -\n20.522  aarch64-linux-g  437815 437814   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections ...\n20.528  cc1              437817 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.531  as               437819 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/cciHWCfI.o\n20.531  rm               437818 435544   0 /usr/bin/rm -f conftest.o\n20.537  powerpc64le-lin  437821 437820   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.543  cc1              437823 437821   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.544  as               437824 437821   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.553  rm               437825 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.558  rm               437826 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.565  cat              437827 430490   0 /usr/bin/cat confdefs.h -\n20.568  rm               437828 430490   0 /usr/bin/rm -f conftest.o conftest\n20.575  riscv64-linux-g  437830 437829   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.582  cc1              437835 437830   0 \n20.584  as               437837 437830   0 \n20.588  cross            437838 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.590  rm               437839 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.590  rustc            437840 437838   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.594  collect2         437849 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAvmzJJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux ...\n20.600  sed              437854 437853   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.600  ld               437861 437849   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAvmzJJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux ...\n20.600  rustc            437840 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.606  cat              437850 435544   0 /usr/bin/cat\n20.610  cat              437873 435544   0 /usr/bin/cat confdefs.h -\n20.613  rm               437874 435544   0 /usr/bin/rm -f conftest.o\n20.631  powerpc64le-lin  437876 437875   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.631  grep             437878 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n20.632  cargo            437879 435532   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n20.632  cat              437880 430490   0 /usr/bin/cat conftest.er1\n20.635  rm               437882 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.635  mv               437884 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.635  cc1              437881 437876   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.639  rm               437885 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.639  as               437883 437876   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.639  cat              437887 430480   0 /usr/bin/cat confdefs.h -\n20.643  sed              437886 430490   0 /usr/bin/sed s/^/| / conftest.c\n20.643  rm               437889 430480   0 /usr/bin/rm -f conftest.o\n20.647  rm               437891 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.648  aarch64-linux-g  437892 437890   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC ...\n20.649  rm               437893 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.652  cat              437895 430490   0 /usr/bin/cat confdefs.h -\n20.652  cc1              437894 437892   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.654  rm               437896 430490   0 /usr/bin/rm -f conftest.o conftest\n20.654  as               437897 437892   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.658  riscv64-linux-g  437899 437898   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.664  cc1              437900 437899   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.667  as               437901 437899   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccQTz9y4.o\n20.674  rustc            437902 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.680  rm               437904 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.681  grep             437903 435544   0 /usr/bin/grep -v ^ *+ conftest.err\n20.685  cat              437906 430480   0 /usr/bin/cat confdefs.h -\n20.685  cat              437905 435544   0 /usr/bin/cat conftest.er1\n20.696  rm               437907 430480   0 /usr/bin/rm -f conftest.o\n20.698  mv               437911 435544   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.699  c++              437913 437912   0 /tmp/native-trace-428093-1783994429368/shims/c++ -c -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE conftest.cpp\n20.701  sed              437914 435544   0 /usr/bin/sed s/^/| / conftest.c\n20.701  c++              437915 437913   0 /usr/bin/c++ -c -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE conftest.cpp\n20.705  cc1plus          437916 437915   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1plus -quiet -imultiarch x86_64-linux-gnu -D_GNU_SOURCE -D _GNU_SOURCE conftest.cpp -quiet -dumpbase conftest.cpp -mtune=generic -march=x86-64 -auxbase conftest -g -gdwarf-4 -O0 -Wimplicit-fallthrough=3 -Wall ...\n20.705  rm               437918 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.708  cat              437919 435544   0 /usr/bin/cat confdefs.h -\n20.715  rm               437923 435544   0 \n20.718  powerpc64le-lin  437925 437924   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.722  cc1              437926 437925   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.723  as               437927 437925   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.728  as               437928 437915   0 /usr/bin/as --64 -o conftest.o /tmp/ccyfXUcj.s\n20.738  rm               437929 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.cpp\n20.749  cat              437931 430480   0 /usr/bin/cat confdefs.h -\n20.754  rm               437936 430480   0 /usr/bin/rm -f conftest.o\n20.757  rustc            437937 437838   0 /home/xmoe/.cargo/bin/rustc -vV\n20.761  aarch64-linux-g  437939 437938   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -Werror -O0 -ffunction-sections -fdata-sections ...\n20.769  cc1              437947 437939   0 \n20.769  build-script-bu  437950 437555   0 /target/debug/build/prettyplease-405734db8e85c51b/build-script-build\n20.769  rustc            437937 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.770  as               437953 437939   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.773  grep             437957 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n20.773  cat              437958 430490   0 /usr/bin/cat conftest.er1\n20.780  rustc            437959 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.787  rustc            437961 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_extra --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fs_extra-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=30051c43fbe457d8 ...\n20.795  mv               437960 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.795  rustc            437964 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n20.796  cargo            437971 437838   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.797  sed              437972 430490   0 /usr/bin/sed s/^/| / conftest.c\n20.804  cargo            437971 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.808  rm               437973 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.810  rm               437987 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.812  rm               437989 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.816  cat              437991 430480   0 /usr/bin/cat confdefs.h -\n20.816  cat              437992 430490   0 /usr/bin/cat confdefs.h -\n20.818  rm               437993 430490   0 /usr/bin/rm -f conftest.o conftest\n20.818  rustc            437983 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name dunce --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dunce-1.0.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=279441eb92ad9cf2 ...\n20.823  rustc            437995 437971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.824  riscv64-linux-g  437996 437994   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.837  as               437998 437996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/cc7F4VhJ.o\n20.837  cc1              437997 437996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.837  rustc            438003 437971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.838  rustc            437988 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --cfg feature=\"unicode\" ...\n20.840  rm               438007 430480   0 /usr/bin/rm -f conftest.o\n20.840  cat              438004 435544   0 /usr/bin/cat confdefs.h -\n20.848  aarch64-linux-g  438012 438011   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -Werror -herror_on_warning -O0 -ffunction-sections ...\n20.850  rm               438017 435544   0 /usr/bin/rm -f conftest.o\n20.850  cc1              438019 438012   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.855  rustc            438025 437971   0 \n20.855  collect2         438027 437996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccG7VIm2.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.855  as               438020 438012   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.856  cc               438001 437612   0 /tmp/native-trace-434802-1783994440811/shims/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustctJitGF/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n20.857  powerpc64le-lin  438030 438029   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.863  cc1              438031 438030   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.872  ld               438039 438027   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccG7VIm2.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.879  cc               438033 438001   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustctJitGF/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n20.886  rustc            438036 434908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n20.904  rustc            438052 437838   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.907  rustc            438013 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.913  rustc            438052 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.922  as               438034 438030   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.923  collect2         438067 438033   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu7ZLRb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.928  rustc            438049 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazy_static --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"spin\", \"spin_no_std\")) -C metadata=9c1da1701740b720 ...\n20.928  ld.lld           438069 438067   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu7ZLRb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160 ...\n20.930  docker           438073 437838   0 /usr/bin/docker --help\n20.933  rm               438075 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.938  cat              438081 430480   0 /usr/bin/cat confdefs.h -\n20.944  rm               438082 430480   0 /usr/bin/rm -f conftest.o conftest\n20.946  aarch64-linux-g  438089 438087   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -Werror -herror_on_warning -O0 ...\n20.949  rust-lld         438069 438067   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu7ZLRb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.951  cc1              438093 438089   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.953  grep             438092 435544   0 /usr/bin/grep -v ^ *+ conftest.err\n20.953  docker           438095 437838   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.954  as               438094 438089   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/ccqEybgs.o\n20.957  cat              438103 435544   0 /usr/bin/cat conftest.er1\n20.960  mv               438104 435544   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.965  sed              438110 435544   0 /usr/bin/sed s/^/| / conftest.c\n20.968  rm               438113 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.971  rustc            438109 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=6583404a194d9851 ...\n20.975  rm               438115 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.976  runc             438116 1599     0 /usr/bin/runc --version\n20.980  cat              438117 435544   0 /usr/bin/cat confdefs.h -\n20.982  docker-init      438123 1599     0 /usr/bin/docker-init --version\n20.982  rm               438124 435544   0 /usr/bin/rm -f conftest.o\n20.983  collect2         438125 438089   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchIDqUo.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.983  docker           438126 437838   0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.986  ld               438127 438125   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchIDqUo.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.987  powerpc64le-lin  438132 438128   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.999  cc1              438137 438132   0 \n21.000  as               438138 438132   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n21.005  runc             438144 425932   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6 --log-format json --systemd-cgroup kill --all ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9 9\n21.009  rustc            438114 432324   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name foundationdb_gen --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/foundationdb-gen-0.9.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"embedded-fdb-include\", \"fdb-5_1\", \"fdb-5_2\", \"fdb-6_0\", \"fdb-6_1\", \"fdb-6_2\", \"fdb-6_3\", \"fdb-7_ -C metadata=d30044ae582d40a2 ...\n21.012  runc             438152 1599     0 /usr/bin/runc --version\n21.017  docker-init      438162 1599     0 /usr/bin/docker-init --version\n21.021  rm               438163 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.049  runc             438166 425932   0 \n21.050  rm               438165 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.054  cat              438174 430490   0 /usr/bin/cat confdefs.h -\n21.056  rustup           438176 437838   0 /home/xmoe/.cargo/bin/rustup toolchain list\n21.060  rm               438177 430490   0 \n21.061  rustc            438159 432324   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clang_sys --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.7.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clang_3_5\" --cfg feature=\"clang_3_6\" --cfg feature=\"clang_3_7\" ...\n21.065  riscv64-linux-g  438187 438184   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n21.070  rustup           438192 437838   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n21.074  cc1              438190 438187   0 \n21.074  as               438194 438187   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccKoVX4I.o\n21.095  rustc            438205 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustc_hash --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-hash-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.102  cat              438206 435544   0 /usr/bin/cat confdefs.h -\n21.108  rustup           438210 437838   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n21.108  rm               438208 435544   0 /usr/bin/rm -f conftest.o\n21.114  powerpc64le-lin  438216 438214   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n21.117  cc1              438227 438216   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n21.119  as               438228 438216   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n21.128  rustc            438193 434908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clang_sys --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clang_3_5\" --cfg feature=\"clang_3_6\" --cfg feature=\"clang_3_7\" ...\n21.133  rm               438234 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.136  rm               438236 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.137  rustc            438235 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name log --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_s -C metadata=cdfd7a6d1c7e8d5d ...\n21.143  cat              438237 430480   0 /usr/bin/cat confdefs.h -\n21.146  collect2         438238 438187   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDKQOf5.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n21.146  rm               438239 430480   0 /usr/bin/rm -f conftest.o conftest\n21.148  ld               438240 438238   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDKQOf5.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n21.149  uname            438242 437838   0 /usr/bin/uname -r\n21.158  aarch64-linux-g  438246 438241   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections ...\n21.161  cc1              438248 438246   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n21.168  as               438251 438246   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/ccG7aQyh.o\n21.168  grep             438252 435544   0 /usr/bin/grep -v ^ *+ conftest.err\n21.173  cat              438254 435544   0 /usr/bin/cat conftest.er1\n21.175  mv               438257 435544   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.178  docker           438263 437838   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n21.182  sed              438268 435544   0 /usr/bin/sed s/^/| / conftest.c\n21.187  rm               438282 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n21.190  cat              438284 435544   0 /usr/bin/cat confdefs.h -\n21.196  rm               438287 435544   0 /usr/bin/rm -f conftest.o\n21.201  powerpc64le-lin  438290 438289   0 \n21.203  cc1              438291 438290   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n21.205  as               438292 438290   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n21.224  rm               438293 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.227  rm               438294 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.227  rustc            438247 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n21.228  cat              438297 430490   0 /usr/bin/cat confdefs.h -\n21.231  rm               438298 430490   0 /usr/bin/rm -f conftest.o conftest\n21.235  riscv64-linux-g  438300 438299   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n21.238  cc1              438302 438300   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n21.240  as               438303 438300   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccwtYp5e.o\n21.248  grep             438301 430480   0 /usr/bin/grep -v ^ *+ conftest.err\n21.253  cat              438310 430480   0 /usr/bin/cat conftest.er1\n21.256  mv               438311 430480   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.260  sed              438315 430480   0 /usr/bin/sed s/^/| / conftest.c\n21.264  rm               438318 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.268  rm               438320 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.274  build-script-bu  438323 437555   0 /target/debug/build/proc-macro2-8db20fd562093160/build-script-build\n"
}
```

#### Record 16

```json
{
  "argv": [
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 426773,
  "build_script_target_dir": "woothee-de9e3cc5c3579e7b",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build",
  "pid": 426773,
  "ppid": 426707,
  "root_cargo_pid": 426707,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "_build_script_out_dir": "/target/debug/build/woothee-de9e3cc5c3579e7b/out"
}
```

#### Record 17

```json
{
  "crate": "woothee",
  "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "event_id": "bsrun:6f1ab56218422645:3bebfad310ac7e4b:edb0efcc32b88a16",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
  "out_dir": "/target/debug/build/woothee-de9e3cc5c3579e7b/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
  "success": true,
  "target": null,
  "version": "0.13.0",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:00:47.367654+00:00",
  "crate": "woothee",
  "version": "0.13.0",
  "architecture": "riscv64",
  "duration_seconds": 29.959447590168566,
  "trace_record_count": 17,
  "trace_owner_summary": {
    "owner_package_count": 42,
    "owner_packages": [
      {
        "crate": "linked-hash-map",
        "version": "0.5.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#linked-hash-map@0.5.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linked-hash-map-0.5.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linked-hash-map-0.5.6/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml"
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
        "crate": "derive_more",
        "version": "0.99.20",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#derive_more@0.99.20",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_more-0.99.20",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_more-0.99.20/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.8.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml"
      },
      {
        "crate": "rustc_version",
        "version": "0.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc_version@0.4.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc_version-0.4.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc_version-0.4.1/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "0.5.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@0.5.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.5.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.5.3/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml"
      },
      {
        "crate": "convert_case",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#convert_case@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/convert_case-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/convert_case-0.4.0/Cargo.toml"
      },
      {
        "crate": "kernel32-sys",
        "version": "0.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#kernel32-sys@0.2.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/kernel32-sys-0.2.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/kernel32-sys-0.2.2/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.3.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.3.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.3.9/Cargo.toml"
      },
      {
        "crate": "serde_core",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml"
      },
      {
        "crate": "thread_local",
        "version": "0.2.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#thread_local@0.2.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-0.2.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-0.2.7/Cargo.toml"
      },
      {
        "crate": "winapi-build",
        "version": "0.1.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-build@0.1.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-build-0.1.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-build-0.1.1/Cargo.toml"
      },
      {
        "crate": "fancy-regex",
        "version": "0.3.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fancy-regex@0.3.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.3.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.3.5/Cargo.toml"
      },
      {
        "crate": "lazy_static",
        "version": "1.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#lazy_static@1.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/Cargo.toml"
      },
      {
        "crate": "serde_yaml",
        "version": "0.8.26",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_yaml@0.8.26",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_yaml-0.8.26",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_yaml-0.8.26/Cargo.toml"
      },
      {
        "crate": "utf8-ranges",
        "version": "0.1.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#utf8-ranges@0.1.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/utf8-ranges-0.1.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/utf8-ranges-0.1.3/Cargo.toml"
      },
      {
        "crate": "hashbrown",
        "version": "0.12.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.12.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3/Cargo.toml"
      },
      {
        "crate": "thread-id",
        "version": "2.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#thread-id@2.0.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread-id-2.0.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread-id-2.0.0/Cargo.toml"
      },
      {
        "crate": "yaml-rust",
        "version": "0.3.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#yaml-rust@0.3.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.3.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.3.5/Cargo.toml"
      },
      {
        "crate": "yaml-rust",
        "version": "0.4.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#yaml-rust@0.4.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.4.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.4.5/Cargo.toml"
      },
      {
        "crate": "indexmap",
        "version": "1.9.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@1.9.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-1.9.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-1.9.3/Cargo.toml"
      },
      {
        "crate": "uap-rust",
        "version": "0.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#uap-rust@0.0.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uap-rust-0.0.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uap-rust-0.0.4/Cargo.toml"
      },
      {
        "crate": "uaparser",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#uaparser@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uaparser-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uaparser-0.4.0/Cargo.toml"
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
        "version": "0.5.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-set@0.5.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.5.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.5.3/Cargo.toml"
      },
      {
        "crate": "bit-vec",
        "version": "0.6.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-vec@0.6.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.6.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.6.3/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "0.1.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@0.1.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-0.1.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-0.1.11/Cargo.toml"
      },
      {
        "crate": "semver",
        "version": "1.0.28",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#semver@1.0.28",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.28",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.28/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml"
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
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "0.1.80",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@0.1.80",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-0.1.80",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-0.1.80/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.2.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.2.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.2.8",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.2.8/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.118",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23/Cargo.toml"
      },
      {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "manifest_path": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 14,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "woothee",
        "version": "0.13.0",
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
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "workspace_root": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@0.5.3",
          "name": "aho-corasick",
          "version": "0.5.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.5.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-0.5.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
          "name": "aho-corasick",
          "version": "1.1.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
          "name": "autocfg",
          "version": "1.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-set@0.5.3",
          "name": "bit-set",
          "version": "0.5.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.5.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-set-0.5.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bit-vec@0.6.3",
          "name": "bit-vec",
          "version": "0.6.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.6.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bit-vec-0.6.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#convert_case@0.4.0",
          "name": "convert_case",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/convert_case-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/convert_case-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#derive_more@0.99.20",
          "name": "derive_more",
          "version": "0.99.20",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_more-0.99.20/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_more-0.99.20"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fancy-regex@0.3.5",
          "name": "fancy-regex",
          "version": "0.3.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.3.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fancy-regex-0.3.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.12.3",
          "name": "hashbrown",
          "version": "0.12.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@1.9.3",
          "name": "indexmap",
          "version": "1.9.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-1.9.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-1.9.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#kernel32-sys@0.2.2",
          "name": "kernel32-sys",
          "version": "0.2.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/kernel32-sys-0.2.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/kernel32-sys-0.2.2"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#linked-hash-map@0.5.6",
          "name": "linked-hash-map",
          "version": "0.5.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linked-hash-map-0.5.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linked-hash-map-0.5.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@0.1.11",
          "name": "memchr",
          "version": "0.1.11",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-0.1.11/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-0.1.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
          "name": "memchr",
          "version": "2.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
          "name": "proc-macro2",
          "version": "1.0.106",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
          "name": "quote",
          "version": "1.0.46",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@0.1.80",
          "name": "regex",
          "version": "0.1.80",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-0.1.80/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-0.1.80"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.3.9",
          "name": "regex-syntax",
          "version": "0.3.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.3.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.3.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
          "name": "regex-syntax",
          "version": "0.8.11",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc_version@0.4.1",
          "name": "rustc_version",
          "version": "0.4.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc_version-0.4.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc_version-0.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.23",
          "name": "ryu",
          "version": "1.0.23",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.23"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#semver@1.0.28",
          "name": "semver",
          "version": "1.0.28",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.28/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.28"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
          "name": "serde",
          "version": "1.0.228",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_yaml@0.8.26",
          "name": "serde_yaml",
          "version": "0.8.26",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_yaml-0.8.26/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_yaml-0.8.26"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
          "name": "syn",
          "version": "2.0.118",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#thread-id@2.0.0",
          "name": "thread-id",
          "version": "2.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread-id-2.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread-id-2.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#thread_local@0.2.7",
          "name": "thread_local",
          "version": "0.2.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-0.2.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thread_local-0.2.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#uap-rust@0.0.4",
          "name": "uap-rust",
          "version": "0.0.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uap-rust-0.0.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uap-rust-0.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#uaparser@0.4.0",
          "name": "uaparser",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uaparser-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uaparser-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
          "name": "unicode-ident",
          "version": "1.0.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#utf8-ranges@0.1.3",
          "name": "utf8-ranges",
          "version": "0.1.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/utf8-ranges-0.1.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/utf8-ranges-0.1.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.2.8",
          "name": "winapi",
          "version": "0.2.8",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.2.8/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.2.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-build@0.1.1",
          "name": "winapi-build",
          "version": "0.1.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-build-0.1.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-build-0.1.1"
        },
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
          "name": "woothee",
          "version": "0.13.0",
          "manifest_path": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#yaml-rust@0.3.5",
          "name": "yaml-rust",
          "version": "0.3.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.3.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.3.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#yaml-rust@0.4.5",
          "name": "yaml-rust",
          "version": "0.4.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.4.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yaml-rust-0.4.5"
        }
      ],
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 426752,
      "ppid": 426727,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "woothee",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "event_id": "used:cc:bd63174f748c2f6e:d8f51a27739a5660:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
      "pid": 426752,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "woothee",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "event_id": "used:cc:bd63174f748c2f6e:2c0c507687cb6078:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
      "pid": 426752,
      "sha256": "4117007a265181226cd649365b3d8ae1d6e250bd1c163fa93b4aaf35f8e5dd4f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "woothee",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "event_id": "used:cc:bd63174f748c2f6e:e848e7213a41b227:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
      "pid": 426752,
      "sha256": "eb140e94e6896f3798bcb62570ca2b1d2c246c64a50afb8570417363c3541cdc",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "woothee",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "event_id": "used:cc:bd63174f748c2f6e:0707bd8802db9734:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
      "pid": 426752,
      "sha256": "3f25d8a6622c8e7e286f9de641bfcbc79dcacb80ded6d9ea2bcd5c6808e3ad3e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "woothee",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "event_id": "used:cc:bd63174f748c2f6e:20c9858ac8bb582e:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
      "pid": 426752,
      "sha256": "bee848b3af42122546b3958d202b5357d08c60f7cc660f3c623098b90baa381a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "woothee",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "event_id": "used:cc:bd63174f748c2f6e:abb4b8088885daab:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
      "pid": 426752,
      "sha256": "d0516df22cc030b9fe63b73240a995c7a33147b153983b3aa576846c13fa5d50",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "woothee",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "event_id": "used:cc:bd63174f748c2f6e:8c6b936929f3828d:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
      "pid": 426752,
      "sha256": "b52374f6cbdb3a7477835154e7ef065d57ae9030b6c77b7f31c72e88c14f94cb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "woothee",
      "cargo_pkg_version": "0.13.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "event_id": "used:cc:bd63174f748c2f6e:4a03c93f0e94f225:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
      "pid": 426752,
      "sha256": "cf9550fcdd6750b8b002d63f481db80394aa13baeaca84880915d0d589ea755d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
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
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "cargo_pkg_name": "woothee",
      "cargo_pkg_version": "0.13.0",
      "context_path": "/tmp/native-trace-426059-1783994423018/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-426059-1783994423018/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 426752,
      "ppid": 426727,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5",
        "/target/debug/build/woothee-de9e3cc5c3579e7b",
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
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcNqg7w5/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.193nbyf.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.193nbyf.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.193nbyf.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.193nbyf.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.193nbyf.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.193nbyf.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.193nbyf.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-426752-1783994425748725622.map",
      "pid": 426752,
      "ppid": 426727,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-426752-1783994425748725622.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
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
      "parsed_event_count": 3979,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 3981,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": ".o\n20.130  sed              437623 437611   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.131  rustc            437627 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n20.131  rustc            437643 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"bytemuck\", \"example_generated\", \"serde\", \"serde_core\", \"std\")) ...\n20.135  aarch64-linux-g  437654 437653   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections -fdata-sections ...\n20.138  cc1              437655 437654   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.139  as               437656 437654   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.139  cat              437657 435544   0 /usr/bin/cat confdefs.h -\n20.141  rm               437658 435544   0 /usr/bin/rm -f conftest.o\n20.155  rustc            437640 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=cc8f9a7b2578854f ...\n20.165  powerpc64le-lin  437661 437659   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.169  cc1              437671 437661   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.175  rm               437678 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.209  cat              437681 430480   0 /usr/bin/cat confdefs.h -\n20.218  rm               437691 430480   0 /usr/bin/rm -f conftest.o conftest\n20.225  aarch64-linux-g  437696 437693   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections ...\n20.229  cc1              437698 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.229  as               437700 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/cc93U75G.o\n20.255  rustc            437644 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.256  rustc            437703 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n20.259  riscv64-linux-g  437652 437650   0 /usr/bin/riscv64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 -ffunction-sections ...\n20.259  rustc            437637 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.69.5/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"logging\" --cfg feature=\"prettyplease\" ...\n20.263  cc1              437706 437652   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.263  rustc            437704 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0919eec9d4c8c0c2 ...\n20.273  rustc            437711 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name linux_raw_sys --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(target_arch, values(\"xtensa\")) --cfg feature=\"elf\" --cfg ...\n20.275  rustc            437710 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.279  rustc            437705 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6cee1ea7c2ce8c63 ...\n20.282  cc               437714 437639   0 /tmp/native-trace-434802-1783994440811/shims/cc -m64 /target/debug/build/prettyplease-405734db8e85c51b/rustcECAZCe/symbols.o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.build_script_build.aaea0e150cf5cfc8-cgu.0. /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.8kx98gngi2nebs6p1mjm4mvsb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.288  rustc            437717 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libloading --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(libloading_docs) --check-cfg cfg(target_os, values(\"cygwin\")) --check-cfg ...\n20.289  rustc            437707 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) ...\n20.296  cc               437720 437714   0 /usr/bin/cc -m64 /target/debug/build/prettyplease-405734db8e85c51b/rustcECAZCe/symbols.o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.build_script_build.aaea0e150cf5cfc8-cgu.0. /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.8kx98gngi2nebs6p1mjm4mvsb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.298  as               437708 437652   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o conftest.o\n20.308  collect2         437724 437720   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.309  rm               437728 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.311  as               437673 437661   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.320  collect2         437735 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctI8CuH.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.322  ld               437737 437735   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctI8CuH.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.326  rm               437738 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.329  rustc            437716 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"std\" --cfg ...\n20.331  cat              437729 430490   0 /usr/bin/cat confdefs.h -\n20.334  rm               437742 430490   0 /usr/bin/rm -f conftest.o conftest\n20.340  sed              437752 437750   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.346  cat              437743 435544   0 /usr/bin/cat\n20.346  riscv64-linux-g  437748 437747   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.350  sed              437759 437758   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.355  cat              437763 435544   0 /usr/bin/cat confdefs.h -\n20.359  rm               437764 435544   0 /usr/bin/rm -f conftest.o\n20.362  powerpc64le-lin  437766 437765   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.365  cc1              437768 437766   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.367  as               437769 437766   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.374  ld.lld           437741 437724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b ...\n20.385  rustc            437770 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazycell --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"clippy\", \"nightly\", \"nightly-testing\", \"serde\")) -C metadata=4ad32744f67d8797 ...\n20.386  cc1              437760 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.389  as               437773 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccBIY51N.o\n20.390  rm               437772 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.391  rust-lld         437741 437724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.431  rm               437774 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.435  cat              437787 430480   0 /usr/bin/cat confdefs.h -\n20.440  rm               437788 430480   0 /usr/bin/rm -f conftest.o\n20.445  aarch64-linux-g  437791 437790   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC ...\n20.446  cc1              437792 437791   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.475  collect2         437785 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJ37tgL.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.479  ld               437796 437785   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJ37tgL.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.480  rm               437797 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.481  as               437793 437791   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.487  sed              437804 437803   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.504  cat              437799 435544   0 /usr/bin/cat\n20.507  rm               437806 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.509  sed              437810 437809   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.509  cat              437811 430480   0 /usr/bin/cat confdefs.h -\n20.512  rm               437812 430480   0 /usr/bin/rm -f conftest.o conftest\n20.521  cat              437816 435544   0 /usr/bin/cat confdefs.h -\n20.522  aarch64-linux-g  437815 437814   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections ...\n20.528  cc1              437817 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.531  as               437819 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/cciHWCfI.o\n20.531  rm               437818 435544   0 /usr/bin/rm -f conftest.o\n20.537  powerpc64le-lin  437821 437820   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.543  cc1              437823 437821   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.544  as               437824 437821   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.553  rm               437825 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.558  rm               437826 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.565  cat              437827 430490   0 /usr/bin/cat confdefs.h -\n20.568  rm               437828 430490   0 /usr/bin/rm -f conftest.o conftest\n20.575  riscv64-linux-g  437830 437829   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.582  cc1              437835 437830   0 \n20.584  as               437837 437830   0 \n20.588  cross            437838 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.590  rm               437839 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.590  rustc            437840 437838   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.594  collect2         437849 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAvmzJJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux ...\n20.600  sed              437854 437853   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.600  ld               437861 437849   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAvmzJJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux ...\n20.600  rustc            437840 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n20.606  cat              437850 435544   0 /usr/bin/cat\n20.610  cat              437873 435544   0 /usr/bin/cat confdefs.h -\n20.613  rm               437874 435544   0 /usr/bin/rm -f conftest.o\n20.631  powerpc64le-lin  437876 437875   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.631  grep             437878 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n20.632  cargo            437879 435532   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n20.632  cat              437880 430490   0 /usr/bin/cat conftest.er1\n20.635  rm               437882 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.635  mv               437884 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.635  cc1              437881 437876   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.639  rm               437885 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.639  as               437883 437876   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.639  cat              437887 430480   0 /usr/bin/cat confdefs.h -\n20.643  sed              437886 430490   0 /usr/bin/sed s/^/| / conftest.c\n20.643  rm               437889 430480   0 /usr/bin/rm -f conftest.o\n20.647  rm               437891 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.648  aarch64-linux-g  437892 437890   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC ...\n20.649  rm               437893 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.652  cat              437895 430490   0 /usr/bin/cat confdefs.h -\n20.652  cc1              437894 437892   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.654  rm               437896 430490   0 /usr/bin/rm -f conftest.o conftest\n20.654  as               437897 437892   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.658  riscv64-linux-g  437899 437898   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.664  cc1              437900 437899   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.667  as               437901 437899   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccQTz9y4.o\n20.674  rustc            437902 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.680  rm               437904 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.681  grep             437903 435544   0 /usr/bin/grep -v ^ *+ conftest.err\n20.685  cat              437906 430480   0 /usr/bin/cat confdefs.h -\n20.685  cat              437905 435544   0 /usr/bin/cat conftest.er1\n20.696  rm               437907 430480   0 /usr/bin/rm -f conftest.o\n20.698  mv               437911 435544   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.699  c++              437913 437912   0 /tmp/native-trace-428093-1783994429368/shims/c++ -c -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE conftest.cpp\n20.701  sed              437914 435544   0 /usr/bin/sed s/^/| / conftest.c\n20.701  c++              437915 437913   0 /usr/bin/c++ -c -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE conftest.cpp\n20.705  cc1plus          437916 437915   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1plus -quiet -imultiarch x86_64-linux-gnu -D_GNU_SOURCE -D _GNU_SOURCE conftest.cpp -quiet -dumpbase conftest.cpp -mtune=generic -march=x86-64 -auxbase conftest -g -gdwarf-4 -O0 -Wimplicit-fallthrough=3 -Wall ...\n20.705  rm               437918 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.708  cat              437919 435544   0 /usr/bin/cat confdefs.h -\n20.715  rm               437923 435544   0 \n20.718  powerpc64le-lin  437925 437924   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.722  cc1              437926 437925   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.723  as               437927 437925   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.728  as               437928 437915   0 /usr/bin/as --64 -o conftest.o /tmp/ccyfXUcj.s\n20.738  rm               437929 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.cpp\n20.749  cat              437931 430480   0 /usr/bin/cat confdefs.h -\n20.754  rm               437936 430480   0 /usr/bin/rm -f conftest.o\n20.757  rustc            437937 437838   0 /home/xmoe/.cargo/bin/rustc -vV\n20.761  aarch64-linux-g  437939 437938   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -Werror -O0 -ffunction-sections -fdata-sections ...\n20.769  cc1              437947 437939   0 \n20.769  build-script-bu  437950 437555   0 /target/debug/build/prettyplease-405734db8e85c51b/build-script-build\n20.769  rustc            437937 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.770  as               437953 437939   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.773  grep             437957 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n20.773  cat              437958 430490   0 /usr/bin/cat conftest.er1\n20.780  rustc            437959 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.787  rustc            437961 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_extra --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fs_extra-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=30051c43fbe457d8 ...\n20.795  mv               437960 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.795  rustc            437964 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n20.796  cargo            437971 437838   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.797  sed              437972 430490   0 /usr/bin/sed s/^/| / conftest.c\n20.804  cargo            437971 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n20.808  rm               437973 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.810  rm               437987 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.812  rm               437989 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.816  cat              437991 430480   0 /usr/bin/cat confdefs.h -\n20.816  cat              437992 430490   0 /usr/bin/cat confdefs.h -\n20.818  rm               437993 430490   0 /usr/bin/rm -f conftest.o conftest\n20.818  rustc            437983 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name dunce --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dunce-1.0.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=279441eb92ad9cf2 ...\n20.823  rustc            437995 437971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n20.824  riscv64-linux-g  437996 437994   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.837  as               437998 437996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/cc7F4VhJ.o\n20.837  cc1              437997 437996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.837  rustc            438003 437971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n20.838  rustc            437988 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --cfg feature=\"unicode\" ...\n20.840  rm               438007 430480   0 /usr/bin/rm -f conftest.o\n20.840  cat              438004 435544   0 /usr/bin/cat confdefs.h -\n20.848  aarch64-linux-g  438012 438011   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -Werror -herror_on_warning -O0 -ffunction-sections ...\n20.850  rm               438017 435544   0 /usr/bin/rm -f conftest.o\n20.850  cc1              438019 438012   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.855  rustc            438025 437971   0 \n20.855  collect2         438027 437996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccG7VIm2.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.855  as               438020 438012   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.856  cc               438001 437612   0 /tmp/native-trace-434802-1783994440811/shims/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustctJitGF/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n20.857  powerpc64le-lin  438030 438029   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.863  cc1              438031 438030   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.872  ld               438039 438027   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccG7VIm2.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.879  cc               438033 438001   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustctJitGF/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n20.886  rustc            438036 434908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n20.904  rustc            438052 437838   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n20.907  rustc            438013 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.913  rustc            438052 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n20.922  as               438034 438030   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.923  collect2         438067 438033   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu7ZLRb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.928  rustc            438049 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazy_static --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"spin\", \"spin_no_std\")) -C metadata=9c1da1701740b720 ...\n20.928  ld.lld           438069 438067   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu7ZLRb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160 ...\n20.930  docker           438073 437838   0 /usr/bin/docker --help\n20.933  rm               438075 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.938  cat              438081 430480   0 /usr/bin/cat confdefs.h -\n20.944  rm               438082 430480   0 /usr/bin/rm -f conftest.o conftest\n20.946  aarch64-linux-g  438089 438087   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -Werror -herror_on_warning -O0 ...\n20.949  rust-lld         438069 438067   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccu7ZLRb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.951  cc1              438093 438089   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.953  grep             438092 435544   0 /usr/bin/grep -v ^ *+ conftest.err\n20.953  docker           438095 437838   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n20.954  as               438094 438089   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/ccqEybgs.o\n20.957  cat              438103 435544   0 /usr/bin/cat conftest.er1\n20.960  mv               438104 435544   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.965  sed              438110 435544   0 /usr/bin/sed s/^/| / conftest.c\n20.968  rm               438113 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.971  rustc            438109 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=6583404a194d9851 ...\n20.975  rm               438115 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.976  runc             438116 1599     0 /usr/bin/runc --version\n20.980  cat              438117 435544   0 /usr/bin/cat confdefs.h -\n20.982  docker-init      438123 1599     0 /usr/bin/docker-init --version\n20.982  rm               438124 435544   0 /usr/bin/rm -f conftest.o\n20.983  collect2         438125 438089   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchIDqUo.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.983  docker           438126 437838   0 /usr/bin/docker info -f {{.SecurityOptions}}\n20.986  ld               438127 438125   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchIDqUo.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.987  powerpc64le-lin  438132 438128   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.999  cc1              438137 438132   0 \n21.000  as               438138 438132   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n21.005  runc             438144 425932   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6 --log-format json --systemd-cgroup kill --all ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9 9\n21.009  rustc            438114 432324   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name foundationdb_gen --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/foundationdb-gen-0.9.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"embedded-fdb-include\", \"fdb-5_1\", \"fdb-5_2\", \"fdb-6_0\", \"fdb-6_1\", \"fdb-6_2\", \"fdb-6_3\", \"fdb-7_ -C metadata=d30044ae582d40a2 ...\n21.012  runc             438152 1599     0 /usr/bin/runc --version\n21.017  docker-init      438162 1599     0 /usr/bin/docker-init --version\n21.021  rm               438163 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.049  runc             438166 425932   0 \n21.050  rm               438165 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.054  cat              438174 430490   0 /usr/bin/cat confdefs.h -\n21.056  rustup           438176 437838   0 /home/xmoe/.cargo/bin/rustup toolchain list\n21.060  rm               438177 430490   0 \n21.061  rustc            438159 432324   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clang_sys --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.7.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clang_3_5\" --cfg feature=\"clang_3_6\" --cfg feature=\"clang_3_7\" ...\n21.065  riscv64-linux-g  438187 438184   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n21.070  rustup           438192 437838   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n21.074  cc1              438190 438187   0 \n21.074  as               438194 438187   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccKoVX4I.o\n21.095  rustc            438205 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustc_hash --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-hash-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.102  cat              438206 435544   0 /usr/bin/cat confdefs.h -\n21.108  rustup           438210 437838   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n21.108  rm               438208 435544   0 /usr/bin/rm -f conftest.o\n21.114  powerpc64le-lin  438216 438214   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n21.117  cc1              438227 438216   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n21.119  as               438228 438216   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n21.128  rustc            438193 434908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clang_sys --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clang_3_5\" --cfg feature=\"clang_3_6\" --cfg feature=\"clang_3_7\" ...\n21.133  rm               438234 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.136  rm               438236 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.137  rustc            438235 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name log --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"kv\", \"kv_serde\", \"kv_std\", \"kv_sval\", \"kv_unstable\", \"kv_unstable_serde\", \"kv_unstable_std\", \"kv_unstable_s -C metadata=cdfd7a6d1c7e8d5d ...\n21.143  cat              438237 430480   0 /usr/bin/cat confdefs.h -\n21.146  collect2         438238 438187   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDKQOf5.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n21.146  rm               438239 430480   0 /usr/bin/rm -f conftest.o conftest\n21.148  ld               438240 438238   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDKQOf5.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n21.149  uname            438242 437838   0 /usr/bin/uname -r\n21.158  aarch64-linux-g  438246 438241   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections ...\n21.161  cc1              438248 438246   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n21.168  as               438251 438246   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/ccG7aQyh.o\n21.168  grep             438252 435544   0 /usr/bin/grep -v ^ *+ conftest.err\n21.173  cat              438254 435544   0 /usr/bin/cat conftest.er1\n21.175  mv               438257 435544   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.178  docker           438263 437838   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n21.182  sed              438268 435544   0 /usr/bin/sed s/^/| / conftest.c\n21.187  rm               438282 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n21.190  cat              438284 435544   0 /usr/bin/cat confdefs.h -\n21.196  rm               438287 435544   0 /usr/bin/rm -f conftest.o\n21.201  powerpc64le-lin  438290 438289   0 \n21.203  cc1              438291 438290   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n21.205  as               438292 438290   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n21.224  rm               438293 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.227  rm               438294 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.227  rustc            438247 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n21.228  cat              438297 430490   0 /usr/bin/cat confdefs.h -\n21.231  rm               438298 430490   0 /usr/bin/rm -f conftest.o conftest\n21.235  riscv64-linux-g  438300 438299   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n21.238  cc1              438302 438300   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n21.240  as               438303 438300   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccwtYp5e.o\n21.248  grep             438301 430480   0 /usr/bin/grep -v ^ *+ conftest.err\n21.253  cat              438310 430480   0 /usr/bin/cat conftest.er1\n21.256  mv               438311 430480   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.260  sed              438315 430480   0 /usr/bin/sed s/^/| / conftest.c\n21.264  rm               438318 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.268  rm               438320 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.274  build-script-bu  438323 437555   0 /target/debug/build/proc-macro2-8db20fd562093160/build-script-build\n"
    },
    {
      "argv": [
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 426773,
      "build_script_target_dir": "woothee-de9e3cc5c3579e7b",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build",
      "pid": 426773,
      "ppid": 426707,
      "root_cargo_pid": 426707,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "woothee",
      "cwd": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "event_id": "bsrun:6f1ab56218422645:3bebfad310ac7e4b:edb0efcc32b88a16",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
      "out_dir": "/target/debug/build/woothee-de9e3cc5c3579e7b/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
      "success": true,
      "target": null,
      "version": "0.13.0",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-riscv64-ht4fag4v/src/woothee-0.13.0",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 1819,
    "crate": "woothee",
    "version": "0.13.0",
    "crate_id": "4987",
    "version_id": "446814",
    "downloads": 8402744,
    "cumulative_downloads": 100329186064,
    "cumulative_share_of_global": 0.3751076651172618,
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
