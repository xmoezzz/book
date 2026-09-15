# `woothee` `0.13.0`

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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL",
    "/target/debug/build/woothee-de9e3cc5c3579e7b",
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
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-426622-1783994425421535432.map",
  "pid": 426622,
  "ppid": 426483,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-426622-1783994425421535432.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "workspace_root": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0"
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
      "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
      "name": "woothee",
      "version": "0.13.0",
      "manifest_path": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0"
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 426622,
  "ppid": 426483,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "event_id": "used:cc:d990f0145ea8b173:fad7cc7d18986985:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
  "pid": 426622,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "event_id": "used:cc:d990f0145ea8b173:a7588d78d4595ae1:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
  "pid": 426622,
  "sha256": "58cd140351832a308bb5c9019ebe5041afead68481a27d7cf175c4b93c428282",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "event_id": "used:cc:d990f0145ea8b173:73280b14fbb84d99:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
  "pid": 426622,
  "sha256": "7be0e3f21002fd4ae65ca43beedd34426b353001b52479774f6fcd0db50619ee",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "event_id": "used:cc:d990f0145ea8b173:3d0a58ca09315d66:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
  "pid": 426622,
  "sha256": "ed74a9eaa046856c0d6227b8997d9be5307a90a31e3d94fe8d2a6e366ec85504",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "event_id": "used:cc:d990f0145ea8b173:2efded3ff9452aca:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
  "pid": 426622,
  "sha256": "2017ac6bbe0262de20c3933245653d31b049c9940288a82ad70fee1ff9025edd",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "event_id": "used:cc:d990f0145ea8b173:b9fa61162eefafd3:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
  "pid": 426622,
  "sha256": "68b557947f9a5923c678ee06d600304df4e372152964f7ad895553f1d85024d8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "event_id": "used:cc:d990f0145ea8b173:5976bcfd8abbdba2:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
  "pid": 426622,
  "sha256": "4e688d1b7cb48d2c7f1123575111360c436c23f569085120747dedd13f8ca77f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "event_id": "used:cc:d990f0145ea8b173:c9f224abaab89887:725cb0c6fd4762da",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
  "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
  "pid": 426622,
  "sha256": "cf9550fcdd6750b8b002d63f481db80394aa13baeaca84880915d0d589ea755d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "cargo_pkg_name": "woothee",
  "cargo_pkg_version": "0.13.0",
  "context_path": "/tmp/native-trace-426070-1783994423032/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-426070-1783994423032/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 426622,
  "ppid": 426483,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL",
    "/target/debug/build/woothee-de9e3cc5c3579e7b",
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
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
      "kind": "object",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-426622-1783994425421535432.map",
  "pid": 426622,
  "ppid": 426483,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-426622-1783994425421535432.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
  "parsed_event_count": 3954,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 3955,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "ux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.168  as               437453 437450   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/cc2daIaP.o\n20.170  sed              437457 437456   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.183  rm               437461 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.186  cat              437462 430480   0 /usr/bin/cat confdefs.h -\n20.189  cat              437475 435544   0 /usr/bin/cat confdefs.h -\n20.191  rm               437481 435544   0 /usr/bin/rm -f conftest.o\n20.192  rm               437480 430480   0 /usr/bin/rm -f conftest.o\n20.198  aarch64-linux-g  437485 437484   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections -fdata-sections ...\n20.201  cc1              437487 437485   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.202  powerpc64le-lin  437488 437486   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.205  as               437490 437485   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.208  cc1              437489 437488   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.210  as               437491 437488   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.218  collect2         437492 437450   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnOheuD.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.220  ld               437493 437492   0 \n20.229  rustc            437459 432324   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"getrandom\" --cfg feature=\"std\" ...\n20.254  rm               437498 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.262  cat              437499 430480   0 /usr/bin/cat confdefs.h -\n20.270  rm               437502 430480   0 /usr/bin/rm -f conftest.o conftest\n20.275  aarch64-linux-g  437504 437503   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections ...\n20.276  rm               437500 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.281  cc1              437505 437504   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.283  rm               437506 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.283  as               437507 437504   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/cc4PWCIc.o\n20.284  rm               437508 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.286  cat              437509 430490   0 /usr/bin/cat confdefs.h -\n20.288  rm               437511 430490   0 /usr/bin/rm -f conftest.o conftest\n20.294  riscv64-linux-g  437517 437513   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections ...\n20.295  sed              437516 437515   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.298  as               437519 437517   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccyGEaoq.o\n20.298  cc1              437518 437517   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.304  cat              437510 435544   0 /usr/bin/cat\n20.313  sed              437526 437524   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.317  build-script-bu  437525 434908   0 /target/debug/build/clang-sys-acca8303cd99ce3c/build-script-build\n20.321  cat              437527 435544   0 /usr/bin/cat confdefs.h -\n20.324  rm               437529 435544   0 /usr/bin/rm -f conftest.o\n20.327  collect2         437530 437517   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdpv5kN.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.327  powerpc64le-lin  437532 437531   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.331  ld               437534 437530   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdpv5kN.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.332  cc1              437535 437532   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.335  as               437538 437532   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.335  build-script-bu  437536 434908   0 /target/debug/build/bindgen-993876236008563c/build-script-build\n20.375  collect2         437543 437504   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDMAdPc.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.376  rm               437542 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.378  ld               437544 437543   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDMAdPc.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.382  sed              437549 437548   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.386  cat              437545 435544   0 /usr/bin/cat\n20.389  sed              437553 437552   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.394  cat              437554 435544   0 /usr/bin/cat confdefs.h -\n20.395  cargo            437555 434802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n20.398  rm               437557 435544   0 /usr/bin/rm -f conftest.o\n20.403  powerpc64le-lin  437559 437558   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.404  grep             437561 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n20.406  cc1              437563 437559   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.406  cat              437562 430490   0 /usr/bin/cat conftest.er1\n20.408  as               437564 437559   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.409  mv               437565 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.414  sed              437566 430490   0 /usr/bin/sed s/^/| / conftest.c\n20.420  rm               437568 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.429  rm               437570 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.429  rustc            437569 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.434  cat              437571 430490   0 /usr/bin/cat\n20.438  cat              437572 430490   0 /usr/bin/cat\n20.444  rm               437576 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.446  cat              437577 430490   0 /usr/bin/cat confdefs.h -\n20.447  rm               437578 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.449  rm               437579 430490   0 /usr/bin/rm -f conftest.o\n20.453  cat              437580 430480   0 /usr/bin/cat confdefs.h -\n20.455  riscv64-linux-g  437582 437581   0 /usr/bin/riscv64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -O0 -ffunction-sections -fdata-sections ...\n20.457  rm               437583 430480   0 \n20.458  cc1              437584 437582   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.460  as               437585 437582   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o conftest.o\n20.460  aarch64-linux-g  437587 437586   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -O0 -ffunction-sections -fdata-sections -fPIC ...\n20.465  cc1              437590 437587   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.466  as               437591 437587   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.470  rm               437588 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.477  sed              437596 437595   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.481  rm               437598 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.483  cat              437599 430490   0 /usr/bin/cat confdefs.h -\n20.485  cat              437592 435544   0 /usr/bin/cat\n20.490  rm               437600 430490   0 /usr/bin/rm -f conftest.o\n20.490  rm               437601 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.494  cat              437605 430480   0 /usr/bin/cat confdefs.h -\n20.496  c++              437607 437604   0 /tmp/native-trace-427759-1783994428532/shims/c++ -c -O3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE conftest.cpp\n20.497  c++              437625 437607   0 /usr/bin/c++ -c -O3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE conftest.cpp\n20.498  rm               437624 430480   0 /usr/bin/rm -f conftest.o\n20.501  grep             437636 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n20.501  rustc            437616 432324   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"meta\" --cfg feature=\"nfa-pikevm\" ...\n20.504  rustc            437634 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name minimal_lexical --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"compact\", \"default\", \"lint\", \"nightly\", \"std\")) ...\n20.506  cat              437638 430490   0 /usr/bin/cat conftest.er1\n20.508  mv               437641 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.508  rustc            437612 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) ...\n20.509  rustc            437635 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name home --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/home-0.5.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::all --warn=clippy::correctness --warn=clippy::self_named_module_files --warn=rust_2018_idioms --allow=rustdoc::private_intra_doc_links --warn=clippy::print_stdout ...\n20.510  sed              437642 430490   0 /usr/bin/sed s/^/| / conftest.cpp\n20.511  rustc            437639 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"verbatim\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) ...\n20.513  rm               437645 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest.cpp\n20.515  cat              437646 430490   0 /usr/bin/cat confdefs.h -\n20.517  rm               437647 430490   0 /usr/bin/rm -f conftest.o\n20.527  sed              437623 437611   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.527  rustc            437627 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n20.527  rustc            437643 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"bytemuck\", \"example_generated\", \"serde\", \"serde_core\", \"std\")) ...\n20.530  aarch64-linux-g  437654 437653   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections -fdata-sections ...\n20.534  cc1              437655 437654   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.535  as               437656 437654   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.535  cat              437657 435544   0 /usr/bin/cat confdefs.h -\n20.537  rm               437658 435544   0 /usr/bin/rm -f conftest.o\n20.551  rustc            437640 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=cc8f9a7b2578854f ...\n20.561  powerpc64le-lin  437661 437659   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.564  cc1              437671 437661   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.570  rm               437678 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.604  cat              437681 430480   0 /usr/bin/cat confdefs.h -\n20.614  rm               437691 430480   0 /usr/bin/rm -f conftest.o conftest\n20.620  aarch64-linux-g  437696 437693   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections ...\n20.625  cc1              437698 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.625  as               437700 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/cc93U75G.o\n20.646  rustc            437703 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n20.647  rustc            437644 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.656  riscv64-linux-g  437652 437650   0 /usr/bin/riscv64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 -ffunction-sections ...\n20.656  rustc            437637 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.69.5/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"logging\" --cfg feature=\"prettyplease\" ...\n20.658  cc1              437706 437652   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.660  rustc            437704 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0919eec9d4c8c0c2 ...\n20.677  rustc            437705 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6cee1ea7c2ce8c63 ...\n20.679  rustc            437710 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.680  rustc            437711 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name linux_raw_sys --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(target_arch, values(\"xtensa\")) --cfg feature=\"elf\" --cfg ...\n20.681  cc               437714 437639   0 /tmp/native-trace-434802-1783994440811/shims/cc -m64 /target/debug/build/prettyplease-405734db8e85c51b/rustcECAZCe/symbols.o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.build_script_build.aaea0e150cf5cfc8-cgu.0. /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.8kx98gngi2nebs6p1mjm4mvsb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.684  rustc            437717 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libloading --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(libloading_docs) --check-cfg cfg(target_os, values(\"cygwin\")) --check-cfg ...\n20.686  rustc            437707 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) ...\n20.695  cc               437720 437714   0 /usr/bin/cc -m64 /target/debug/build/prettyplease-405734db8e85c51b/rustcECAZCe/symbols.o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.build_script_build.aaea0e150cf5cfc8-cgu.0. /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.8kx98gngi2nebs6p1mjm4mvsb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.695  as               437708 437652   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o conftest.o\n20.703  collect2         437724 437720   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.706  rm               437728 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.706  as               437673 437661   0 \n20.716  collect2         437735 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctI8CuH.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.718  ld               437737 437735   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctI8CuH.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.722  rm               437738 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.725  rustc            437716 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"std\" --cfg ...\n20.726  cat              437729 430490   0 /usr/bin/cat confdefs.h -\n20.729  rm               437742 430490   0 /usr/bin/rm -f conftest.o conftest\n20.737  sed              437752 437750   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.742  cat              437743 435544   0 /usr/bin/cat\n20.742  riscv64-linux-g  437748 437747   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.747  sed              437759 437758   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.751  cat              437763 435544   0 /usr/bin/cat confdefs.h -\n20.754  rm               437764 435544   0 /usr/bin/rm -f conftest.o\n20.758  powerpc64le-lin  437766 437765   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.761  cc1              437768 437766   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.763  as               437769 437766   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.773  ld.lld           437741 437724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b ...\n20.781  rustc            437770 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazycell --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"clippy\", \"nightly\", \"nightly-testing\", \"serde\")) -C metadata=4ad32744f67d8797 ...\n20.782  cc1              437760 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.784  as               437773 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccBIY51N.o\n20.786  rm               437772 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.787  rust-lld         437741 437724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.827  rm               437774 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.830  cat              437787 430480   0 /usr/bin/cat confdefs.h -\n20.836  rm               437788 430480   0 /usr/bin/rm -f conftest.o\n20.839  aarch64-linux-g  437791 437790   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC ...\n20.842  cc1              437792 437791   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.871  collect2         437785 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJ37tgL.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.875  ld               437796 437785   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJ37tgL.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.876  rm               437797 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.877  as               437793 437791   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.883  sed              437804 437803   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.900  cat              437799 435544   0 /usr/bin/cat\n20.902  rm               437806 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.904  sed              437810 437809   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.905  cat              437811 430480   0 \n20.908  rm               437812 430480   0 /usr/bin/rm -f conftest.o conftest\n20.918  aarch64-linux-g  437815 437814   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections ...\n20.918  cat              437816 435544   0 /usr/bin/cat confdefs.h -\n20.925  cc1              437817 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.927  rm               437818 435544   0 /usr/bin/rm -f conftest.o\n20.927  as               437819 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/cciHWCfI.o\n20.933  powerpc64le-lin  437821 437820   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.939  cc1              437823 437821   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.941  as               437824 437821   0 \n20.949  rm               437825 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.953  rm               437826 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.961  cat              437827 430490   0 /usr/bin/cat confdefs.h -\n20.965  rm               437828 430490   0 /usr/bin/rm -f conftest.o conftest\n20.971  riscv64-linux-g  437830 437829   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.978  cc1              437835 437830   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.979  as               437837 437830   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccfMEcOA.o\n20.985  cross            437838 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.986  rm               437839 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.987  rustc            437840 437838   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.989  collect2         437849 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAvmzJJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux ...\n20.996  sed              437854 437853   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.996  ld               437861 437849   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAvmzJJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux ...\n20.996  rustc            437840 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.003  cat              437850 435544   0 /usr/bin/cat\n21.006  cat              437873 435544   0 /usr/bin/cat confdefs.h -\n21.011  rm               437874 435544   0 /usr/bin/rm -f conftest.o\n21.026  powerpc64le-lin  437876 437875   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n21.026  grep             437878 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n21.027  cargo            437879 435532   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n21.028  cat              437880 430490   0 /usr/bin/cat conftest.er1\n21.029  rm               437882 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.030  cc1              437881 437876   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n21.031  mv               437884 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.031  as               437883 437876   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n21.032  rm               437885 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.037  cat              437887 430480   0 /usr/bin/cat confdefs.h -\n21.038  sed              437886 430490   0 /usr/bin/sed s/^/| / conftest.c\n21.038  rm               437889 430480   0 /usr/bin/rm -f conftest.o\n21.044  rm               437891 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.044  aarch64-linux-g  437892 437890   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC ...\n21.046  rm               437893 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.048  cat              437895 430490   0 /usr/bin/cat confdefs.h -\n21.048  cc1              437894 437892   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n21.050  rm               437896 430490   0 /usr/bin/rm -f conftest.o conftest\n21.050  as               437897 437892   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n21.054  riscv64-linux-g  437899 437898   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n21.060  cc1              437900 437899   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n21.063  as               437901 437899   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccQTz9y4.o\n21.070  rustc            437902 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.077  rm               437904 430480   0 \n21.077  grep             437903 435544   0 /usr/bin/grep -v ^ *+ conftest.err\n21.081  cat              437906 430480   0 /usr/bin/cat confdefs.h -\n21.081  cat              437905 435544   0 /usr/bin/cat conftest.er1\n21.091  rm               437907 430480   0 /usr/bin/rm -f conftest.o\n21.093  mv               437911 435544   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.095  c++              437913 437912   0 /tmp/native-trace-428093-1783994429368/shims/c++ -c -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE conftest.cpp\n21.097  sed              437914 435544   0 /usr/bin/sed s/^/| / conftest.c\n21.097  c++              437915 437913   0 /usr/bin/c++ -c -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE conftest.cpp\n21.100  cc1plus          437916 437915   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1plus -quiet -imultiarch x86_64-linux-gnu -D_GNU_SOURCE -D _GNU_SOURCE conftest.cpp -quiet -dumpbase conftest.cpp -mtune=generic -march=x86-64 -auxbase conftest -g -gdwarf-4 -O0 -Wimplicit-fallthrough=3 -Wall ...\n21.101  rm               437918 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n21.104  cat              437919 435544   0 /usr/bin/cat confdefs.h -\n21.111  rm               437923 435544   0 /usr/bin/rm -f conftest.o\n21.114  powerpc64le-lin  437925 437924   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n21.120  cc1              437926 437925   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n21.120  as               437927 437925   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n21.125  as               437928 437915   0 /usr/bin/as --64 -o conftest.o /tmp/ccyfXUcj.s\n21.135  rm               437929 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.cpp\n21.146  cat              437931 430480   0 /usr/bin/cat confdefs.h -\n21.150  rm               437936 430480   0 /usr/bin/rm -f conftest.o\n21.153  rustc            437937 437838   0 /home/xmoe/.cargo/bin/rustc -vV\n21.158  aarch64-linux-g  437939 437938   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -Werror -O0 -ffunction-sections -fdata-sections ...\n21.163  rustc            437937 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.163  build-script-bu  437950 437555   0 /target/debug/build/prettyplease-405734db8e85c51b/build-script-build\n21.164  cc1              437947 437939   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n21.166  as               437953 437939   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n21.167  grep             437957 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n21.169  cat              437958 430490   0 /usr/bin/cat conftest.er1\n21.177  rustc            437959 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.187  rustc            437961 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_extra --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fs_extra-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=30051c43fbe457d8 ...\n21.190  mv               437960 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.191  rustc            437964 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n21.192  cargo            437971 437838   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.193  sed              437972 430490   0 /usr/bin/sed s/^/| / conftest.c\n21.202  cargo            437971 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.205  rm               437973 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.207  rm               437987 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n21.208  rm               437989 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.211  cat              437991 430480   0 /usr/bin/cat confdefs.h -\n21.211  cat              437992 430490   0 /usr/bin/cat confdefs.h -\n21.212  rustc            437983 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name dunce --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dunce-1.0.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=279441eb92ad9cf2 ...\n21.213  rm               437993 430490   0 /usr/bin/rm -f conftest.o conftest\n21.229  as               437998 437996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/cc7F4VhJ.o\n21.230  riscv64-linux-g  437996 437994   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n21.230  cc1              437997 437996   0 \n21.230  rustc            437995 437971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.232  rustc            437988 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --cfg feature=\"unicode\" ...\n21.232  rustc            438003 437971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.235  cat              438004 435544   0 /usr/bin/cat confdefs.h -\n21.236  rm               438007 430480   0 /usr/bin/rm -f conftest.o\n21.243  aarch64-linux-g  438012 438011   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -Werror -herror_on_warning -O0 -ffunction-sections ...\n21.247  cc1              438019 438012   0 \n21.247  rm               438017 435544   0 /usr/bin/rm -f conftest.o\n21.249  rustc            438025 437971   0 \n21.250  collect2         438027 437996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccG7VIm2.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n21.252  as               438020 438012   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n21.252  cc               438001 437612   0 /tmp/native-trace-434802-1783994440811/shims/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustctJitGF/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.253  powerpc64le-lin  438030 438029   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n21.258  cc1              438031 438030   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n21.268  ld               438039 438027   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccG7VIm2.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n21.276  cc               438033 438001   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustctJitGF/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.282  rustc            438036 434908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n"
}
```

#### Record 16

```json
{
  "argv": [
    "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 426678,
  "build_script_target_dir": "woothee-de9e3cc5c3579e7b",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build",
  "pid": 426678,
  "ppid": 426386,
  "root_cargo_pid": 426386,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "_build_script_out_dir": "/target/debug/build/woothee-de9e3cc5c3579e7b/out"
}
```

#### Record 17

```json
{
  "crate": "woothee",
  "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "event_id": "bsrun:a560ea17cdb5df52:3bebfad310ac7e4b:edb0efcc32b88a16",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
  "out_dir": "/target/debug/build/woothee-de9e3cc5c3579e7b/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
  "success": true,
  "target": null,
  "version": "0.13.0",
  "_owner": {
    "crate": "woothee",
    "version": "0.13.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:00:47.071026+00:00",
  "crate": "woothee",
  "version": "0.13.0",
  "architecture": "ppc64le",
  "duration_seconds": 29.660504191182554,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "manifest_path": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "workspace_root": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0"
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
          "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
          "name": "woothee",
          "version": "0.13.0",
          "manifest_path": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0"
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 426622,
      "ppid": 426483,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "event_id": "used:cc:d990f0145ea8b173:fad7cc7d18986985:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
      "pid": 426622,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "event_id": "used:cc:d990f0145ea8b173:a7588d78d4595ae1:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
      "pid": 426622,
      "sha256": "58cd140351832a308bb5c9019ebe5041afead68481a27d7cf175c4b93c428282",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "event_id": "used:cc:d990f0145ea8b173:73280b14fbb84d99:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
      "pid": 426622,
      "sha256": "7be0e3f21002fd4ae65ca43beedd34426b353001b52479774f6fcd0db50619ee",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "event_id": "used:cc:d990f0145ea8b173:3d0a58ca09315d66:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
      "pid": 426622,
      "sha256": "ed74a9eaa046856c0d6227b8997d9be5307a90a31e3d94fe8d2a6e366ec85504",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "event_id": "used:cc:d990f0145ea8b173:2efded3ff9452aca:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
      "pid": 426622,
      "sha256": "2017ac6bbe0262de20c3933245653d31b049c9940288a82ad70fee1ff9025edd",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "event_id": "used:cc:d990f0145ea8b173:b9fa61162eefafd3:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
      "pid": 426622,
      "sha256": "68b557947f9a5923c678ee06d600304df4e372152964f7ad895553f1d85024d8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "event_id": "used:cc:d990f0145ea8b173:5976bcfd8abbdba2:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
      "pid": 426622,
      "sha256": "4e688d1b7cb48d2c7f1123575111360c436c23f569085120747dedd13f8ca77f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "event_id": "used:cc:d990f0145ea8b173:c9f224abaab89887:725cb0c6fd4762da",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b",
      "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
      "pid": 426622,
      "sha256": "cf9550fcdd6750b8b002d63f481db80394aa13baeaca84880915d0d589ea755d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "cargo_pkg_name": "woothee",
      "cargo_pkg_version": "0.13.0",
      "context_path": "/tmp/native-trace-426070-1783994423032/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-426070-1783994423032/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 426622,
      "ppid": 426483,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL",
        "/target/debug/build/woothee-de9e3cc5c3579e7b",
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
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/rustcYbOphL/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.0im7d2o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.0im7d2o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.0im7d2o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.0im7d2o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.0im7d2o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.0im7d2o.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/woothee-de9e3cc5c3579e7b",
          "kind": "object",
          "path": "/target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.0im7d2o.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-426622-1783994425421535432.map",
      "pid": 426622,
      "ppid": 426483,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-426622-1783994425421535432.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
      "parsed_event_count": 3954,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 3955,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "ux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.168  as               437453 437450   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/cc2daIaP.o\n20.170  sed              437457 437456   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.183  rm               437461 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.186  cat              437462 430480   0 /usr/bin/cat confdefs.h -\n20.189  cat              437475 435544   0 /usr/bin/cat confdefs.h -\n20.191  rm               437481 435544   0 /usr/bin/rm -f conftest.o\n20.192  rm               437480 430480   0 /usr/bin/rm -f conftest.o\n20.198  aarch64-linux-g  437485 437484   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections -fdata-sections ...\n20.201  cc1              437487 437485   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.202  powerpc64le-lin  437488 437486   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.205  as               437490 437485   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.208  cc1              437489 437488   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.210  as               437491 437488   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.218  collect2         437492 437450   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnOheuD.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.220  ld               437493 437492   0 \n20.229  rustc            437459 432324   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"getrandom\" --cfg feature=\"std\" ...\n20.254  rm               437498 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.262  cat              437499 430480   0 /usr/bin/cat confdefs.h -\n20.270  rm               437502 430480   0 /usr/bin/rm -f conftest.o conftest\n20.275  aarch64-linux-g  437504 437503   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections ...\n20.276  rm               437500 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.281  cc1              437505 437504   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.283  rm               437506 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.283  as               437507 437504   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/cc4PWCIc.o\n20.284  rm               437508 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.286  cat              437509 430490   0 /usr/bin/cat confdefs.h -\n20.288  rm               437511 430490   0 /usr/bin/rm -f conftest.o conftest\n20.294  riscv64-linux-g  437517 437513   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections ...\n20.295  sed              437516 437515   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.298  as               437519 437517   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccyGEaoq.o\n20.298  cc1              437518 437517   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.304  cat              437510 435544   0 /usr/bin/cat\n20.313  sed              437526 437524   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.317  build-script-bu  437525 434908   0 /target/debug/build/clang-sys-acca8303cd99ce3c/build-script-build\n20.321  cat              437527 435544   0 /usr/bin/cat confdefs.h -\n20.324  rm               437529 435544   0 /usr/bin/rm -f conftest.o\n20.327  collect2         437530 437517   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdpv5kN.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.327  powerpc64le-lin  437532 437531   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.331  ld               437534 437530   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdpv5kN.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.332  cc1              437535 437532   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.335  as               437538 437532   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.335  build-script-bu  437536 434908   0 /target/debug/build/bindgen-993876236008563c/build-script-build\n20.375  collect2         437543 437504   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDMAdPc.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.376  rm               437542 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.378  ld               437544 437543   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDMAdPc.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.382  sed              437549 437548   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.386  cat              437545 435544   0 /usr/bin/cat\n20.389  sed              437553 437552   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.394  cat              437554 435544   0 /usr/bin/cat confdefs.h -\n20.395  cargo            437555 434802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n20.398  rm               437557 435544   0 /usr/bin/rm -f conftest.o\n20.403  powerpc64le-lin  437559 437558   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.404  grep             437561 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n20.406  cc1              437563 437559   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.406  cat              437562 430490   0 /usr/bin/cat conftest.er1\n20.408  as               437564 437559   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.409  mv               437565 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.414  sed              437566 430490   0 /usr/bin/sed s/^/| / conftest.c\n20.420  rm               437568 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.429  rm               437570 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.429  rustc            437569 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n20.434  cat              437571 430490   0 /usr/bin/cat\n20.438  cat              437572 430490   0 /usr/bin/cat\n20.444  rm               437576 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.446  cat              437577 430490   0 /usr/bin/cat confdefs.h -\n20.447  rm               437578 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.449  rm               437579 430490   0 /usr/bin/rm -f conftest.o\n20.453  cat              437580 430480   0 /usr/bin/cat confdefs.h -\n20.455  riscv64-linux-g  437582 437581   0 /usr/bin/riscv64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -O0 -ffunction-sections -fdata-sections ...\n20.457  rm               437583 430480   0 \n20.458  cc1              437584 437582   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.460  as               437585 437582   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o conftest.o\n20.460  aarch64-linux-g  437587 437586   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -O0 -ffunction-sections -fdata-sections -fPIC ...\n20.465  cc1              437590 437587   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.466  as               437591 437587   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.470  rm               437588 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.477  sed              437596 437595   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.481  rm               437598 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.483  cat              437599 430490   0 /usr/bin/cat confdefs.h -\n20.485  cat              437592 435544   0 /usr/bin/cat\n20.490  rm               437600 430490   0 /usr/bin/rm -f conftest.o\n20.490  rm               437601 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.494  cat              437605 430480   0 /usr/bin/cat confdefs.h -\n20.496  c++              437607 437604   0 /tmp/native-trace-427759-1783994428532/shims/c++ -c -O3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE conftest.cpp\n20.497  c++              437625 437607   0 /usr/bin/c++ -c -O3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE conftest.cpp\n20.498  rm               437624 430480   0 /usr/bin/rm -f conftest.o\n20.501  grep             437636 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n20.501  rustc            437616 432324   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"meta\" --cfg feature=\"nfa-pikevm\" ...\n20.504  rustc            437634 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name minimal_lexical --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/minimal-lexical-0.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"compact\", \"default\", \"lint\", \"nightly\", \"std\")) ...\n20.506  cat              437638 430490   0 /usr/bin/cat conftest.er1\n20.508  mv               437641 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n20.508  rustc            437612 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) ...\n20.509  rustc            437635 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name home --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/home-0.5.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::all --warn=clippy::correctness --warn=clippy::self_named_module_files --warn=rust_2018_idioms --allow=rustdoc::private_intra_doc_links --warn=clippy::print_stdout ...\n20.510  sed              437642 430490   0 /usr/bin/sed s/^/| / conftest.cpp\n20.511  rustc            437639 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prettyplease-0.2.37/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"verbatim\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"verbatim\")) ...\n20.513  rm               437645 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest.cpp\n20.515  cat              437646 430490   0 /usr/bin/cat confdefs.h -\n20.517  rm               437647 430490   0 /usr/bin/rm -f conftest.o\n20.527  sed              437623 437611   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.527  rustc            437627 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n20.527  rustc            437643 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bitflags --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"bytemuck\", \"example_generated\", \"serde\", \"serde_core\", \"std\")) ...\n20.530  aarch64-linux-g  437654 437653   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections -fdata-sections ...\n20.534  cc1              437655 437654   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.535  as               437656 437654   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.535  cat              437657 435544   0 /usr/bin/cat confdefs.h -\n20.537  rm               437658 435544   0 /usr/bin/rm -f conftest.o\n20.551  rustc            437640 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=cc8f9a7b2578854f ...\n20.561  powerpc64le-lin  437661 437659   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.564  cc1              437671 437661   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.570  rm               437678 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.604  cat              437681 430480   0 /usr/bin/cat confdefs.h -\n20.614  rm               437691 430480   0 /usr/bin/rm -f conftest.o conftest\n20.620  aarch64-linux-g  437696 437693   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Werror -herror_on_warning -O0 -ffunction-sections ...\n20.625  cc1              437698 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.625  as               437700 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/cc93U75G.o\n20.646  rustc            437703 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.44/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(alloc_c_string) --check-cfg cfg(alloc_ffi) --check-cfg ...\n20.647  rustc            437644 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.16.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.656  riscv64-linux-g  437652 437650   0 /usr/bin/riscv64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 -ffunction-sections ...\n20.656  rustc            437637 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.69.5/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"logging\" --cfg feature=\"prettyplease\" ...\n20.658  cc1              437706 437652   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.660  rustc            437704 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0919eec9d4c8c0c2 ...\n20.677  rustc            437705 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=6cee1ea7c2ce8c63 ...\n20.679  rustc            437710 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n20.680  rustc            437711 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name linux_raw_sys --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(target_arch, values(\"xtensa\")) --cfg feature=\"elf\" --cfg ...\n20.681  cc               437714 437639   0 /tmp/native-trace-434802-1783994440811/shims/cc -m64 /target/debug/build/prettyplease-405734db8e85c51b/rustcECAZCe/symbols.o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.build_script_build.aaea0e150cf5cfc8-cgu.0. /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.8kx98gngi2nebs6p1mjm4mvsb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.684  rustc            437717 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libloading --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libloading-0.8.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(libloading_docs) --check-cfg cfg(target_os, values(\"cygwin\")) --check-cfg ...\n20.686  rustc            437707 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) ...\n20.695  cc               437720 437714   0 /usr/bin/cc -m64 /target/debug/build/prettyplease-405734db8e85c51b/rustcECAZCe/symbols.o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.build_script_build.aaea0e150cf5cfc8-cgu.0. /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b.8kx98gngi2nebs6p1mjm4mvsb.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n20.695  as               437708 437652   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o conftest.o\n20.703  collect2         437724 437720   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n20.706  rm               437728 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.706  as               437673 437661   0 \n20.716  collect2         437735 437696   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctI8CuH.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.718  ld               437737 437735   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctI8CuH.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -h error_on_warning --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X ...\n20.722  rm               437738 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.725  rustc            437716 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"std\" --cfg ...\n20.726  cat              437729 430490   0 /usr/bin/cat confdefs.h -\n20.729  rm               437742 430490   0 /usr/bin/rm -f conftest.o conftest\n20.737  sed              437752 437750   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.742  cat              437743 435544   0 /usr/bin/cat\n20.742  riscv64-linux-g  437748 437747   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.747  sed              437759 437758   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.751  cat              437763 435544   0 /usr/bin/cat confdefs.h -\n20.754  rm               437764 435544   0 /usr/bin/rm -f conftest.o\n20.758  powerpc64le-lin  437766 437765   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.761  cc1              437768 437766   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.763  as               437769 437766   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n20.773  ld.lld           437741 437724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/prettyplease-405734db8e85c51b/build_script_build-405734db8e85c51b ...\n20.781  rustc            437770 437555   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazycell --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazycell-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"clippy\", \"nightly\", \"nightly-testing\", \"serde\")) -C metadata=4ad32744f67d8797 ...\n20.782  cc1              437760 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.784  as               437773 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccBIY51N.o\n20.786  rm               437772 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.787  rust-lld         437741 437724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDZ7ikv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n20.827  rm               437774 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.830  cat              437787 430480   0 /usr/bin/cat confdefs.h -\n20.836  rm               437788 430480   0 /usr/bin/rm -f conftest.o\n20.839  aarch64-linux-g  437791 437790   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC ...\n20.842  cc1              437792 437791   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.871  collect2         437785 437748   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJ37tgL.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.875  ld               437796 437785   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJ37tgL.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n20.876  rm               437797 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.877  as               437793 437791   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n20.883  sed              437804 437803   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.900  cat              437799 435544   0 /usr/bin/cat\n20.902  rm               437806 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.904  sed              437810 437809   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n20.905  cat              437811 430480   0 \n20.908  rm               437812 430480   0 /usr/bin/rm -f conftest.o conftest\n20.918  aarch64-linux-g  437815 437814   0 /usr/bin/aarch64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections ...\n20.918  cat              437816 435544   0 /usr/bin/cat confdefs.h -\n20.925  cc1              437817 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n20.927  rm               437818 435544   0 /usr/bin/rm -f conftest.o\n20.927  as               437819 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /tmp/cciHWCfI.o\n20.933  powerpc64le-lin  437821 437820   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n20.939  cc1              437823 437821   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n20.941  as               437824 437821   0 \n20.949  rm               437825 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n20.953  rm               437826 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n20.961  cat              437827 430490   0 /usr/bin/cat confdefs.h -\n20.965  rm               437828 430490   0 /usr/bin/rm -f conftest.o conftest\n20.971  riscv64-linux-g  437830 437829   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n20.978  cc1              437835 437830   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n20.979  as               437837 437830   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccfMEcOA.o\n20.985  cross            437838 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n20.986  rm               437839 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n20.987  rustc            437840 437838   0 /home/xmoe/.cargo/bin/rustc --print target-list\n20.989  collect2         437849 437815   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/collect2 -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAvmzJJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux ...\n20.996  sed              437854 437853   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n20.996  ld               437861 437849   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/aarch64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/aarch64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAvmzJJ.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr --hash-style=gnu --as-needed -dynamic-linker /lib/ld-linux-aarch64.so.1 -X -EL -maarch64linux ...\n20.996  rustc            437840 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n21.003  cat              437850 435544   0 /usr/bin/cat\n21.006  cat              437873 435544   0 /usr/bin/cat confdefs.h -\n21.011  rm               437874 435544   0 /usr/bin/rm -f conftest.o\n21.026  powerpc64le-lin  437876 437875   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n21.026  grep             437878 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n21.027  cargo            437879 435532   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n21.028  cat              437880 430490   0 /usr/bin/cat conftest.er1\n21.029  rm               437882 430480   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.030  cc1              437881 437876   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n21.031  mv               437884 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.031  as               437883 437876   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n21.032  rm               437885 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.037  cat              437887 430480   0 /usr/bin/cat confdefs.h -\n21.038  sed              437886 430490   0 /usr/bin/sed s/^/| / conftest.c\n21.038  rm               437889 430480   0 /usr/bin/rm -f conftest.o\n21.044  rm               437891 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.044  aarch64-linux-g  437892 437890   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC ...\n21.046  rm               437893 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.048  cat              437895 430490   0 /usr/bin/cat confdefs.h -\n21.048  cc1              437894 437892   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n21.050  rm               437896 430490   0 /usr/bin/rm -f conftest.o conftest\n21.050  as               437897 437892   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n21.054  riscv64-linux-g  437899 437898   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n21.060  cc1              437900 437899   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g3 ...\n21.063  as               437901 437899   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/ccQTz9y4.o\n21.070  rustc            437902 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n21.077  rm               437904 430480   0 \n21.077  grep             437903 435544   0 /usr/bin/grep -v ^ *+ conftest.err\n21.081  cat              437906 430480   0 /usr/bin/cat confdefs.h -\n21.081  cat              437905 435544   0 /usr/bin/cat conftest.er1\n21.091  rm               437907 430480   0 /usr/bin/rm -f conftest.o\n21.093  mv               437911 435544   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.095  c++              437913 437912   0 /tmp/native-trace-428093-1783994429368/shims/c++ -c -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE conftest.cpp\n21.097  sed              437914 435544   0 /usr/bin/sed s/^/| / conftest.c\n21.097  c++              437915 437913   0 /usr/bin/c++ -c -fvisibility=hidden -Wimplicit-fallthrough -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE conftest.cpp\n21.100  cc1plus          437916 437915   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1plus -quiet -imultiarch x86_64-linux-gnu -D_GNU_SOURCE -D _GNU_SOURCE conftest.cpp -quiet -dumpbase conftest.cpp -mtune=generic -march=x86-64 -auxbase conftest -g -gdwarf-4 -O0 -Wimplicit-fallthrough=3 -Wall ...\n21.101  rm               437918 435544   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n21.104  cat              437919 435544   0 /usr/bin/cat confdefs.h -\n21.111  rm               437923 435544   0 /usr/bin/rm -f conftest.o\n21.114  powerpc64le-lin  437925 437924   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n21.120  cc1              437926 437925   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n21.120  as               437927 437925   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o conftest.o\n21.125  as               437928 437915   0 /usr/bin/as --64 -o conftest.o /tmp/ccyfXUcj.s\n21.135  rm               437929 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.cpp\n21.146  cat              437931 430480   0 /usr/bin/cat confdefs.h -\n21.150  rm               437936 430480   0 /usr/bin/rm -f conftest.o\n21.153  rustc            437937 437838   0 /home/xmoe/.cargo/bin/rustc -vV\n21.158  aarch64-linux-g  437939 437938   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -Werror -O0 -ffunction-sections -fdata-sections ...\n21.163  rustc            437937 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.163  build-script-bu  437950 437555   0 /target/debug/build/prettyplease-405734db8e85c51b/build-script-build\n21.164  cc1              437947 437939   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu -dD -D _GNU_SOURCE conftest.c -quiet -dumpbase conftest.c -mlittle-endian -mabi=lp64 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 ...\n21.166  as               437953 437939   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n21.167  grep             437957 430490   0 /usr/bin/grep -v ^ *+ conftest.err\n21.169  cat              437958 430490   0 /usr/bin/cat conftest.er1\n21.177  rustc            437959 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n21.187  rustc            437961 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fs_extra --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fs_extra-1.3.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=30051c43fbe457d8 ...\n21.190  mv               437960 430490   0 /usr/bin/mv -f conftest.er1 conftest.err\n21.191  rustc            437964 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n21.192  cargo            437971 437838   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.193  sed              437972 430490   0 /usr/bin/sed s/^/| / conftest.c\n21.202  cargo            437971 437838   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n21.205  rm               437973 430490   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n21.207  rm               437987 430480   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n21.208  rm               437989 430490   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n21.211  cat              437991 430480   0 /usr/bin/cat confdefs.h -\n21.211  cat              437992 430490   0 /usr/bin/cat confdefs.h -\n21.212  rustc            437983 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name dunce --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/dunce-1.0.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=279441eb92ad9cf2 ...\n21.213  rm               437993 430490   0 /usr/bin/rm -f conftest.o conftest\n21.229  as               437998 437996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /tmp/cc7F4VhJ.o\n21.230  riscv64-linux-g  437996 437994   0 /usr/bin/riscv64-linux-gnu-gcc -o conftest -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -O3 -funroll-loops -O0 ...\n21.230  cc1              437997 437996   0 \n21.230  rustc            437995 437971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.232  rustc            437988 437879   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --cfg feature=\"unicode\" ...\n21.232  rustc            438003 437971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n21.235  cat              438004 435544   0 /usr/bin/cat confdefs.h -\n21.236  rm               438007 430480   0 /usr/bin/rm -f conftest.o\n21.243  aarch64-linux-g  438012 438011   0 /usr/bin/aarch64-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -fvisibility=hidden -Wimplicit-fallthrough -Werror -herror_on_warning -O0 -ffunction-sections ...\n21.247  cc1              438019 438012   0 \n21.247  rm               438017 435544   0 /usr/bin/rm -f conftest.o\n21.249  rustc            438025 437971   0 \n21.250  collect2         438027 437996   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/collect2 -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccG7VIm2.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n21.252  as               438020 438012   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o conftest.o\n21.252  cc               438001 437612   0 /tmp/native-trace-434802-1783994440811/shims/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustctJitGF/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.253  powerpc64le-lin  438030 438029   0 /usr/bin/powerpc64le-linux-gnu-gcc -c -std=gnu11 -Wall -Wextra -Wsign-compare -Wundef -Wno-format-zero-length -Wpointer-arith -Wno-missing-braces -Wno-missing-field-initializers -Wno-missing-attributes -pipe -g3 -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 ...\n21.258  cc1              438031 438030   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu -dD conftest.c -msecure-plt -quiet -dumpbase conftest.c -m64 -mcpu=power8 -auxbase conftest -g3 -g -gdwarf-4 -g -gdwarf-4 -O0 ...\n21.268  ld               438039 438027   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/ld -plugin /usr/lib/gcc-cross/riscv64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc-cross/riscv64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccG7VIm2.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -hash-style=gnu --as-needed -melf64lriscv -dynamic-linker /lib/ld-linux-riscv64-lp64d.so.1 -pie -z ...\n21.276  cc               438033 438001   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-8db20fd562093160/rustctJitGF/symbols.o /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.0.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.build_script_build.4f3236f108d8c613-cgu.1.r /target/debug/build/proc-macro2-8db20fd562093160/build_script_build-8db20fd562093160.ckx9xd4gt0eahw97v78jtpuhu.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n21.282  rustc            438036 434908   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n"
    },
    {
      "argv": [
        "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 426678,
      "build_script_target_dir": "woothee-de9e3cc5c3579e7b",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build",
      "pid": 426678,
      "ppid": 426386,
      "root_cargo_pid": 426386,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "woothee",
      "cwd": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "event_id": "bsrun:a560ea17cdb5df52:3bebfad310ac7e4b:edb0efcc32b88a16",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
      "out_dir": "/target/debug/build/woothee-de9e3cc5c3579e7b/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
      "success": true,
      "target": null,
      "version": "0.13.0",
      "_owner": {
        "crate": "woothee",
        "version": "0.13.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0#woothee@0.13.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-02oa5p6r/src/woothee-0.13.0",
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
