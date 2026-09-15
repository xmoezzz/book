# `lock_api` `0.4.12`

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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
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
  "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse",
    "/target/debug/build/lock_api-39921d1064022982",
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
      "directory": "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-30235-1783992705326601512.map",
  "pid": 30235,
  "ppid": 30151,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-30235-1783992705326601512.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "workspace_root": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
      "name": "autocfg",
      "version": "1.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
    },
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
      "name": "lock_api",
      "version": "0.4.12",
      "manifest_path": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
      "name": "scopeguard",
      "version": "1.2.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0"
    }
  ],
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "exit_code": 0,
  "kind": "exec",
  "pid": 30235,
  "ppid": 30151,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "lock_api",
  "cargo_pkg_version": "0.4.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "event_id": "used:cc:075bd4cb4c3b736c:7f599dd7bbad9bc0:b9c6b36ff3d57106",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
  "path": "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
  "pid": 30235,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "lock_api",
  "cargo_pkg_version": "0.4.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "event_id": "used:cc:075bd4cb4c3b736c:bc3d4f4a833ca6e2:b9c6b36ff3d57106",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
  "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
  "pid": 30235,
  "sha256": "4af8ee46cbef4fac1a9b011f7ff09194f173e06bb11f4362ecc8a6a75b2d5475",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "lock_api",
  "cargo_pkg_version": "0.4.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "event_id": "used:cc:075bd4cb4c3b736c:2c5a255d7a6ea480:b9c6b36ff3d57106",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
  "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
  "pid": 30235,
  "sha256": "9e8a2676f71bd6c4161cc6476b2327c8f0770e938b4ce822cbc2aa63976186c4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "lock_api",
  "cargo_pkg_version": "0.4.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "event_id": "used:cc:075bd4cb4c3b736c:bc58f6af6c3b879a:b9c6b36ff3d57106",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
  "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
  "pid": 30235,
  "sha256": "f3de507dee5f10f0b8902aec785c29e5d229c419ae58c37a020246608c819a90",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "lock_api",
  "cargo_pkg_version": "0.4.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "event_id": "used:cc:075bd4cb4c3b736c:e4800f2ff71ecbff:b9c6b36ff3d57106",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
  "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
  "pid": 30235,
  "sha256": "72b55d9ed06f91be084a680b6741dfad1be53c143675fed760b25fcd25f2c3d3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "lock_api",
  "cargo_pkg_version": "0.4.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "event_id": "used:cc:075bd4cb4c3b736c:9df6148d0268cb8c:b9c6b36ff3d57106",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
  "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
  "pid": 30235,
  "sha256": "1720fb99d31eba17ea425e9f0fea5713bbe105642d512df6ce0d2aad4a6836ca",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "lock_api",
  "cargo_pkg_version": "0.4.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "event_id": "used:cc:075bd4cb4c3b736c:4705f451ac8dfc6f:b9c6b36ff3d57106",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
  "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
  "pid": 30235,
  "sha256": "7880150aa9e4eed010a3b987919f8f04d7a932f695376d83bed7e400e429000d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "lock_api",
  "cargo_pkg_version": "0.4.12",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "event_id": "used:cc:075bd4cb4c3b736c:227243562110debf:b9c6b36ff3d57106",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
  "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
  "pid": 30235,
  "sha256": "5df3020f1bba3edcb95751cfa8655d556545514b428e8fc8c4ca9a044febe235",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
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
  "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "cargo_pkg_name": "lock_api",
  "cargo_pkg_version": "0.4.12",
  "context_path": "/tmp/native-trace-28430-1783992700226/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-28430-1783992700226/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 30235,
  "ppid": 30151,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse",
    "/target/debug/build/lock_api-39921d1064022982",
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
      "directory": "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/lock_api-39921d1064022982",
      "kind": "object",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-30235-1783992705326601512.map",
  "pid": 30235,
  "ppid": 30151,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-30235-1783992705326601512.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
  "parsed_event_count": 371,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 373,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "x-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-gfp_p384.o /tmp/cc1w7Gg7.s\n2.090   riscv64-linux-g  30897  30722    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align ...\n2.091   powerpc64le-lin  30898  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.092   cc1              30900  30898    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/bn/montgomery.c -msecure-plt -quiet -dumpbase montgomery.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery.o ...\n2.092   cc1              30899  30897    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -imultilib . -imultiarch riscv64-linux-gnu -dD -D NDEBUG /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/limbs/limbs.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/ -dumpbase aaa1ba3e455ee2e1-limbs.c -dumpbase-ext ...\n2.102   aarch64-linux-g  30901  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.104   cc1              30902  30901    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/fipsmodule/ec/p256.c -quiet -dumpbase p256.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256.o -gdwarf-4 ...\n2.111   as               30903  30898    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery.o /tmp/cc315ypx.s\n2.118   as               30904  30901    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256.o /tmp/ccXIvgBL.s\n2.119   as               30906  30897    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/aaa1ba3e455ee2e1-limbs.o /tmp/ccEPZcuf.s\n2.120   powerpc64le-lin  30905  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.122   cc1              30907  30905    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/bn/montgomery_inv.c -msecure-plt -quiet -dumpbase montgomery_inv.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery_inv.o ...\n2.128   riscv64-linux-g  30908  30722    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align ...\n2.130   cc1              30910  30908    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -imultilib . -imultiarch riscv64-linux-gnu -dD -D NDEBUG /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/mem.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/ -dumpbase a4019cc0736b0423-mem.c -dumpbase-ext ...\n2.132   aarch64-linux-g  30909  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.134   cc1              30911  30909    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/limbs/limbs.c -quiet -dumpbase limbs.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/aaa1ba3e455ee2e1-limbs.o -gdwarf-4 ...\n2.138   as               30912  30905    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery_inv.o /tmp/ccAPijB5.s\n2.144   as               30913  30908    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a4019cc0736b0423-mem.o /tmp/cctdf2Dr.s\n2.147   powerpc64le-lin  30914  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.149   cc1              30915  30914    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/ec/ecp_nistz.c -msecure-plt -quiet -dumpbase ecp_nistz.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-ecp_nistz.o ...\n2.152   riscv64-linux-g  30916  30722    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align ...\n2.154   cc1              30917  30916    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -imultilib . -imultiarch riscv64-linux-gnu -dD -D NDEBUG /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/poly1305/poly1305.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/ -dumpbase d5a9841f3dc6e253-poly1305.c -dumpbase-ext ...\n2.163   as               30918  30909    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/aaa1ba3e455ee2e1-limbs.o /tmp/ccUoUlBo.s\n2.165   as               30919  30914    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-ecp_nistz.o /tmp/ccD4VS8K.s\n2.174   powerpc64le-lin  30920  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.176   cc1              30921  30920    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/ec/gfp_p256.c -msecure-plt -quiet -dumpbase gfp_p256.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p256.o ...\n2.177   as               30923  30916    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/d5a9841f3dc6e253-poly1305.o /tmp/ccX8WPKW.s\n2.179   aarch64-linux-g  30922  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.181   cc1              30924  30922    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/mem.c -quiet -dumpbase mem.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-mem.o -gdwarf-4 ...\n2.187   riscv64-linux-g  30925  30722    0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/libring_core_0_17_14_.a /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/25ac62e5b3c53843-curve25519.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/0bbbd18bda93c05b-aes_nohw.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/00c879ee3285a50d-montgomery.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/00c879ee3285a50d-montgomery_inv.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a0330e891e733f4e-ecp_nistz.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a0330e891e733f4e-gfp_p256.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a0330e891e733f4e-gfp_p384.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a0330e891e733f4e-p256.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/aaa1ba3e455ee2e1-limbs.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a4019cc0736b0423-mem.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/d5a9841f3dc6e253-poly1305.o\n2.193   as               30926  30920    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p256.o /tmp/ccjuXbIe.s\n2.198   as               30927  30922    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-mem.o /tmp/ccdrLoKn.s\n2.203   powerpc64le-lin  30928  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.205   cc1              30929  30928    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/ec/gfp_p384.c -msecure-plt -quiet -dumpbase gfp_p384.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p384.o ...\n2.213   aarch64-linux-g  30930  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.215   cc1              30931  30930    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/poly1305/poly1305.c -quiet -dumpbase poly1305.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/d5a9841f3dc6e253-poly1305.o -gdwarf-4 ...\n2.234   riscv64-linux-g  30932  30722    0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/libring_core_0_17_14_.a\n2.239   as               30933  30930    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/d5a9841f3dc6e253-poly1305.o /tmp/ccCGPFfZ.s\n2.244   as               30934  30928    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p384.o /tmp/ccwrjzfQ.s\n2.254   aarch64-linux-g  30935  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.255   cc1              30937  30935    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/fipsmodule/ec/p256-nistz.c -quiet -dumpbase p256-nistz.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256-nistz.o -gdwarf-4 ...\n2.257   powerpc64le-lin  30936  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.258   cc1              30938  30936    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/ec/p256.c -msecure-plt -quiet -dumpbase p256.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-p256.o ...\n2.261   riscv64-linux-g  30939  30722    0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/13067934521883617256detect_compiler_family.c\n2.263   cc1              30940  30939    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/13067934521883617256detect_compiler_family.c -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 13067934521883617256detect_compiler_family.c -dumpbase-ext .c\n2.269   riscv64-linux-g  30941  30722    0 /usr/bin/riscv64-linux-gnu-gcc -?\n2.274   riscv64-linux-g  30942  30722    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align ...\n2.276   cc1              30943  30942    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -imultilib . -imultiarch riscv64-linux-gnu -dD -D NDEBUG /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/constant_time_test.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/ -dumpbase a4019cc0736b0423-constant_time_test.c -dumpbase-ext ...\n2.296   as               30944  30942    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a4019cc0736b0423-constant_time_test.o /tmp/ccruuUYq.s\n2.303   riscv64-linux-g  30945  30722    0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/libring_core_0_17_14__test.a /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a4019cc0736b0423-constant_time_test.o\n2.314   as               30946  30936    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-p256.o /tmp/ccTiUGVs.s\n2.321   riscv64-linux-g  30947  30722    0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/libring_core_0_17_14__test.a\n2.327   powerpc64le-lin  30948  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.329   cc1              30949  30948    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/limbs/limbs.c -msecure-plt -quiet -dumpbase limbs.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/aaa1ba3e455ee2e1-limbs.o ...\n2.344   rustc            30951  28923    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ring --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"dev_urandom_fallback\" ...\n2.355   runc             30955  3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process2723051921 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n2.357   as               30959  30948    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/aaa1ba3e455ee2e1-limbs.o /tmp/cchhnp2l.s\n2.362   exe              30963  30955    0 /proc/self/exe init\n2.368   powerpc64le-lin  30966  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.370   cc1              30972  30966    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/mem.c -msecure-plt -quiet -dumpbase mem.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-mem.o ...\n2.384   etcdctl          30965  30955    0 /usr/local/bin/etcdctl endpoint health\n2.385   as               30973  30966    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-mem.o /tmp/ccBgQASJ.s\n2.387   as               30974  30935    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256-nistz.o /tmp/ccSS8VRk.s\n2.394   powerpc64le-lin  30983  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.397   cc1              30984  30983    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/poly1305/poly1305.c -msecure-plt -quiet -dumpbase poly1305.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/d5a9841f3dc6e253-poly1305.o ...\n2.408   aarch64-linux-g  30985  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.410   cc1              30986  30985    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/chacha-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.416   as               30987  30985    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-chacha-armv8-linux64.o /tmp/ccmYUWl8.s\n2.422   as               30988  30983    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/d5a9841f3dc6e253-poly1305.o /tmp/cceG20FZ.s\n2.429   aarch64-linux-g  30989  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.431   cc1              30991  30989    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/chacha20_poly1305_armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.432   powerpc64le-lin  30990  30855    0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/libring_core_0_17_14_.a /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/25ac62e5b3c53843-curve25519.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/0bbbd18bda93c05b-aes_nohw.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery_inv.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-ecp_nistz.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p256.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p384.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-p256.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/aaa1ba3e455ee2e1-limbs.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-mem.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/d5a9841f3dc6e253-poly1305.o\n2.438   as               30992  30989    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-chacha20_poly1305_armv8-linux64.o /tmp/ccTOii5p.s\n2.439   powerpc64le-lin  30993  30855    0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/libring_core_0_17_14_.a\n2.445   powerpc64le-lin  30994  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/7603557205145803586detect_compiler_family.c\n2.446   cc1              30995  30994    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/7603557205145803586detect_compiler_family.c -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n2.451   powerpc64le-lin  30996  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n2.454   aarch64-linux-g  30997  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.456   powerpc64le-lin  30998  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.457   cc1              30999  30997    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/aesv8-armx-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.458   cc1              31000  30998    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/constant_time_test.c -msecure-plt -quiet -dumpbase constant_time_test.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-constant_time_test.o ...\n2.463   as               31001  30997    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-aesv8-armx-linux64.o /tmp/ccckEXz1.s\n2.474   aarch64-linux-g  31002  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.476   cc1              31003  31002    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/aesv8-gcm-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.481   as               31004  30998    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-constant_time_test.o /tmp/ccoNgP15.s\n2.482   as               31005  31002    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-aesv8-gcm-armv8-linux64.o /tmp/ccpOuwXq.s\n2.491   powerpc64le-lin  31006  30855    0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/libring_core_0_17_14__test.a /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-constant_time_test.o\n2.493   powerpc64le-lin  31007  30855    0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/libring_core_0_17_14__test.a\n2.495   aarch64-linux-g  31008  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.497   cc1              31009  31008    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/ghash-neon-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.501   rustc            31011  29208    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ring --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"dev_urandom_fallback\" ...\n2.503   as               31012  31008    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-ghash-neon-armv8-linux64.o /tmp/ccoJfkJQ.s\n2.514   aarch64-linux-g  31016  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.516   cc1              31017  31016    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/ghashv8-armx-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.522   as               31018  31016    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-ghashv8-armx-linux64.o /tmp/ccRCniPs.s\n2.534   aarch64-linux-g  31019  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.535   cc1              31020  31019    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/vpaes-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.542   as               31021  31019    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-vpaes-armv8-linux64.o /tmp/cc2DbBjJ.s\n2.553   aarch64-linux-g  31022  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.555   cc1              31023  31022    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/armv8-mont-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.562   as               31024  31022    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-armv8-mont-linux64.o /tmp/cckUevwX.s\n2.574   aarch64-linux-g  31025  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.576   cc1              31026  31025    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/p256-armv8-asm-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.583   as               31027  31025    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-p256-armv8-asm-linux64.o /tmp/ccYYbLjb.s\n2.596   aarch64-linux-g  31028  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.599   cc1              31029  31028    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/sha512-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.604   as               31030  31028    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-sha512-armv8-linux64.o /tmp/ccDnB7Gq.s\n2.617   aarch64-linux-g  31031  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.618   cc1              31032  31031    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/sha256-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.625   as               31033  31031    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-sha256-armv8-linux64.o /tmp/ccQIagMC.s\n2.638   aarch64-linux-g  31034  30748    0 /usr/bin/aarch64-linux-gnu-ar cq /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/libring_core_0_17_14_.a /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/25ac62e5b3c53843-curve25519.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/0bbbd18bda93c05b-aes_nohw.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/00c879ee3285a50d-montgomery.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/00c879ee3285a50d-montgomery_inv.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-ecp_nistz.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-gfp_p256.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-gfp_p384.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/aaa1ba3e455ee2e1-limbs.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-mem.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/d5a9841f3dc6e253-poly1305.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256-nistz.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-chacha-armv8-linux64.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-chacha20_poly1305_armv8-linux64.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-aesv8-armx-linux64.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-aesv8-gcm-armv8-linux64.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-ghash-neon-armv8-linux64.o ...\n2.647   aarch64-linux-g  31035  30748    0 /usr/bin/aarch64-linux-gnu-ar s /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/libring_core_0_17_14_.a\n2.655   aarch64-linux-g  31036  30748    0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/7011150007031298944detect_compiler_family.c\n2.656   cc1              31037  31036    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/7011150007031298944detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n2.661   aarch64-linux-g  31038  30748    0 /usr/bin/aarch64-linux-gnu-gcc -?\n2.665   aarch64-linux-g  31039  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.667   cc1              31040  31039    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/constant_time_test.c -quiet -dumpbase constant_time_test.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-constant_time_test.o -gdwarf-4 ...\n2.690   as               31041  31039    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-constant_time_test.o /tmp/ccxoI22b.s\n2.704   aarch64-linux-g  31042  30748    0 /usr/bin/aarch64-linux-gnu-ar cq /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/libring_core_0_17_14__test.a /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-constant_time_test.o\n2.707   aarch64-linux-g  31043  30748    0 /usr/bin/aarch64-linux-gnu-ar s /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/libring_core_0_17_14__test.a\n2.715   rustc            31045  29032    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ring --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"dev_urandom_fallback\" ...\n4.030   git              31817  2235138   0 /usr/bin/git config --get commit.template\n4.046   git              31818  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n4.061   git              31819  2235138   0 /usr/bin/git status -z -uall\n4.076   git              31820  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n4.272   sh               31821  2147557   0 /bin/sh -c which ps\n4.274   which            31821  2147557   0 /usr/bin/which ps\n4.276   sh               31822  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n4.277   ps               31822  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n4.300   sh               31823  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n4.302   cpuUsage.sh      31823  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n4.303   sed              31824  31823    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n4.305   cat              31825  31823    0 /usr/bin/cat /proc/2240539/stat\n4.307   cat              31826  31823    0 /usr/bin/cat /proc/4193716/stat\n4.308   sleep            31827  31823    0 /usr/bin/sleep 1\n4.521   git              31829  2235138   0 /usr/bin/git worktree list --porcelain\n5.310   sed              31830  31823    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n5.312   cat              31831  31823    0 /usr/bin/cat /proc/2240539/stat\n5.314   cat              31833  31823    0 /usr/bin/cat /proc/4193716/stat\n5.383   16               31835  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n5.401   frpc             31835  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n9.099   git              31842  2235138   0 /usr/bin/git config --get commit.template\n9.118   git              31843  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n9.139   git              31844  2235138   0 /usr/bin/git status -z -uall\n9.159   git              31845  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n14.907  runc             31847  4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process791607860 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n14.913  exe              31854  31847    0 /proc/self/exe init\n14.934  curl             31856  31847    0 /usr/bin/curl -f http://localhost:9091/healthz\n15.897  runc             31866  25919    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5 --log-format json --systemd-cgroup kill --all 6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5a0adf 9\n15.906  runc             31872  25919    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5 --log-format json --systemd-cgroup delete 6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5a0adf\n16.071  containerd-shim  31878  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5a0adf -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5 delete\n16.074  runc             31885  31878    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5a0ad --log-format json delete --force 6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5a0adf\n16.126  sh               31894  31890    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth8d33afa\n16.128  sed              31896  31894    0 /usr/bin/sed -n s/^driver: //p\n16.128  ethtool          31895  31894    0 /usr/sbin/ethtool -i veth8d33afa\n16.136  systemd-sysctl   31899  31890    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8d33afa --prefix=/net/ipv4/neigh/veth8d33afa --prefix=/net/ipv6/conf/veth8d33afa --prefix=/net/ipv6/neigh/veth8d33afa\n16.883  sh               31906  2147557   0 /bin/sh -c which ps\n16.885  which            31906  2147557   0 /usr/bin/which ps\n16.887  sh               31907  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.890  ps               31907  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.920  sh               31908  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.921  cpuUsage.sh      31908  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.923  sed              31909  31908    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.926  cat              31910  31908    0 /usr/bin/cat /proc/2240539/stat\n16.928  cat              31911  31908    0 \n16.929  sleep            31912  31908    0 /usr/bin/sleep 1\n17.114  runc             31914  27017    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1 --log-format json --systemd-cgroup kill --all aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1c2de4 9\n17.133  runc             31920  27017    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1 --log-format json --systemd-cgroup delete aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1c2de4\n17.301  git              31926  2235138   0 /usr/bin/git config --get commit.template\n17.321  git              31927  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n17.328  containerd-shim  31928  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1c2de4 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1 delete\n17.331  runc             31935  31928    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1c2de --log-format json delete --force aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1c2de4\n17.342  git              31938  2235138   0 /usr/bin/git status -z -uall\n17.361  git              31941  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n17.372  systemd-sysctl   31942  31890    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf419e17 --prefix=/net/ipv4/neigh/vethf419e17 --prefix=/net/ipv6/conf/vethf419e17 --prefix=/net/ipv6/neigh/vethf419e17\n17.627  runc             31944  27816    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83 --log-format json --systemd-cgroup kill --all af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83c5764 9\n17.647  runc             31950  27816    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83 --log-format json --systemd-cgroup delete af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83c5764\n17.836  containerd-shim  31956  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83c5764 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83 delete\n17.839  runc             31963  31956    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83c576 --log-format json delete --force af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83c5764\n17.884  systemd-sysctl   31969  31943    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5033a9f --prefix=/net/ipv4/neigh/veth5033a9f --prefix=/net/ipv6/conf/veth5033a9f --prefix=/net/ipv6/neigh/veth5033a9f\n17.931  sed              31970  31908    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.934  cat              31971  31908    0 /usr/bin/cat /proc/2240539/stat\n17.936  cat              31973  31908    0 /usr/bin/cat /proc/4193716/stat\n17.960  runc             31975  25626    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5016ad3988b64adfc45e2f6872bf60289eaeaf4e4fd40b1739c81a92de5 --log-format json --systemd-cgroup kill --all 5016ad3988b64adfc45e2f6872bf60289eaeaf4e4fd40b1739c81a92de58d1ec 9\n17.968  runc             31981  28208    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f0 --log-format json --systemd-cgroup kill --all 96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f045866 9\n17.977  runc             31988  28208    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f0 --log-format json --systemd-cgroup delete 96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f045866\n17.980  runc             31994  25626    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5016ad3988b64adfc45e2f6872bf60289eaeaf4e4fd40b1739c81a92de5 --log-format json --systemd-cgroup delete 5016ad3988b64adfc45e2f6872bf60289eaeaf4e4fd40b1739c81a92de58d1ec\n18.066  runc             32000  28082    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/34a9607f36f42f3715f2bbb2bc80c9844ae22a434476eedafd85fa6c911 --log-format json --systemd-cgroup kill --all 34a9607f36f42f3715f2bbb2bc80c9844ae22a434476eedafd85fa6c911ba296 9\n18.074  runc             32006  28082    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/34a9607f36f42f3715f2bbb2bc80c9844ae22a434476eedafd85fa6c911 --log-format json --systemd-cgroup delete 34a9607f36f42f3715f2bbb2bc80c9844ae22a434476eedafd85fa6c911ba296\n18.114  runc             32013  27492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b0980f18dae85a9701abc50dcde6ee99e938103ccdbfb553dde921ae73d --log-format json --systemd-cgroup kill --all b0980f18dae85a9701abc50dcde6ee99e938103ccdbfb553dde921ae73d03fbc 9\n18.122  runc             32019  27492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b0980f18dae85a9701abc50dcde6ee99e938103ccdbfb553dde921ae73d --log-format json --systemd-cgroup delete b0980f18dae85a9701abc50dcde6ee99e938103ccdbfb553dde921ae73d03fbc\n18.195  containerd-shim  32025  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f045866 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f0 delete\n18.197  runc             32030  28291    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/67fa9a024237996e4049d5cfcbf2f5183367331030b1d2499d22df7973b --log-format json --systemd-cgroup kill --all 67fa9a024237996e4049d5cfcbf2f5183367331030b1d2499d22df7973b8b760 9\n18.198  runc             32039  32025    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f04586 --log-format json delete --force 96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f045866\n18.205  runc             32044  28291    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/67fa9a024237996e4049d5cfcbf2f5183367331030b1d2499d22df7973b --log-format json --systemd-cgroup delete 67fa9a024237996e4049d5cfcbf2f5183367331030b1d2499d22df7973b8b760\n18.251  systemd-sysctl   32050  31943    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth41b3fe5 --prefix=/net/ipv4/neigh/veth41b3fe5 --prefix=/net/ipv6/conf/veth41b3fe5 --prefix=/net/ipv6/neigh/veth41b3fe5\n"
}
```

#### Record 16

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 30353,
  "build_script_target_dir": "lock_api-39921d1064022982",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 30355,
  "ppid": 30353,
  "root_cargo_pid": 29713,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "_build_script_out_dir": "/target/debug/build/lock_api-39921d1064022982/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 17

```json
{
  "argv": [
    "/target/debug/build/lock_api-39921d1064022982/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 30353,
  "build_script_target_dir": "lock_api-39921d1064022982",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/lock_api-39921d1064022982/build-script-build",
  "pid": 30353,
  "ppid": 29713,
  "root_cargo_pid": 29713,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "_build_script_out_dir": "/target/debug/build/lock_api-39921d1064022982/out"
}
```

#### Record 18

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_0a36ac03abfe7b95_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/lock_api-6a1572496f12bfd4/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 30353,
  "build_script_target_dir": "lock_api-39921d1064022982",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 30378,
  "ppid": 30353,
  "root_cargo_pid": 29713,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "_build_script_out_dir": "/target/debug/build/lock_api-39921d1064022982/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 19

```json
{
  "crate": "lock_api",
  "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "event_id": "bsrun:46bf16e519a33b29:00d165f8f4401f24:e8ac304c4608595a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/lock_api-39921d1064022982/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
  "out_dir": "/target/debug/build/lock_api-39921d1064022982/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
  "success": true,
  "target": null,
  "version": "0.4.12",
  "_owner": {
    "crate": "lock_api",
    "version": "0.4.12",
    "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
    "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
    "source": "cwd_prefix"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 30353,
  "build_script_target_dir": "lock_api-39921d1064022982",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 30355,
  "ppid": 30353,
  "root_cargo_pid": 29713,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 21

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_0a36ac03abfe7b95_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/lock_api-6a1572496f12bfd4/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 30353,
  "build_script_target_dir": "lock_api-39921d1064022982",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 30378,
  "ppid": 30353,
  "root_cargo_pid": 29713,
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
  "time": "2026-07-14T01:32:03.501806+00:00",
  "crate": "lock_api",
  "version": "0.4.12",
  "architecture": "riscv64",
  "duration_seconds": 29.141564399935305,
  "trace_record_count": 19,
  "trace_owner_summary": {
    "owner_package_count": 3,
    "owner_packages": [
      {
        "crate": "scopeguard",
        "version": "1.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml"
      },
      {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "manifest_path": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12/Cargo.toml"
      }
    ],
    "attributed_event_count": 14,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "lock_api",
        "version": "0.4.12",
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
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "workspace_root": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
          "name": "autocfg",
          "version": "1.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
        },
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
          "name": "lock_api",
          "version": "0.4.12",
          "manifest_path": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
          "name": "scopeguard",
          "version": "1.2.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0"
        }
      ],
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "exit_code": 0,
      "kind": "exec",
      "pid": 30235,
      "ppid": 30151,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "lock_api",
      "cargo_pkg_version": "0.4.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "event_id": "used:cc:075bd4cb4c3b736c:7f599dd7bbad9bc0:b9c6b36ff3d57106",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
      "path": "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
      "pid": 30235,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "lock_api",
      "cargo_pkg_version": "0.4.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "event_id": "used:cc:075bd4cb4c3b736c:bc3d4f4a833ca6e2:b9c6b36ff3d57106",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
      "pid": 30235,
      "sha256": "4af8ee46cbef4fac1a9b011f7ff09194f173e06bb11f4362ecc8a6a75b2d5475",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "lock_api",
      "cargo_pkg_version": "0.4.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "event_id": "used:cc:075bd4cb4c3b736c:2c5a255d7a6ea480:b9c6b36ff3d57106",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
      "pid": 30235,
      "sha256": "9e8a2676f71bd6c4161cc6476b2327c8f0770e938b4ce822cbc2aa63976186c4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "lock_api",
      "cargo_pkg_version": "0.4.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "event_id": "used:cc:075bd4cb4c3b736c:bc58f6af6c3b879a:b9c6b36ff3d57106",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
      "pid": 30235,
      "sha256": "f3de507dee5f10f0b8902aec785c29e5d229c419ae58c37a020246608c819a90",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "lock_api",
      "cargo_pkg_version": "0.4.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "event_id": "used:cc:075bd4cb4c3b736c:e4800f2ff71ecbff:b9c6b36ff3d57106",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
      "pid": 30235,
      "sha256": "72b55d9ed06f91be084a680b6741dfad1be53c143675fed760b25fcd25f2c3d3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "lock_api",
      "cargo_pkg_version": "0.4.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "event_id": "used:cc:075bd4cb4c3b736c:9df6148d0268cb8c:b9c6b36ff3d57106",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
      "pid": 30235,
      "sha256": "1720fb99d31eba17ea425e9f0fea5713bbe105642d512df6ce0d2aad4a6836ca",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "lock_api",
      "cargo_pkg_version": "0.4.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "event_id": "used:cc:075bd4cb4c3b736c:4705f451ac8dfc6f:b9c6b36ff3d57106",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
      "pid": 30235,
      "sha256": "7880150aa9e4eed010a3b987919f8f04d7a932f695376d83bed7e400e429000d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "lock_api",
      "cargo_pkg_version": "0.4.12",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "event_id": "used:cc:075bd4cb4c3b736c:227243562110debf:b9c6b36ff3d57106",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
      "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
      "pid": 30235,
      "sha256": "5df3020f1bba3edcb95751cfa8655d556545514b428e8fc8c4ca9a044febe235",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
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
      "output": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "cargo_pkg_name": "lock_api",
      "cargo_pkg_version": "0.4.12",
      "context_path": "/tmp/native-trace-28430-1783992700226/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-28430-1783992700226/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 30235,
      "ppid": 30151,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse",
        "/target/debug/build/lock_api-39921d1064022982",
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
          "directory": "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse",
          "kind": "object",
          "path": "/target/debug/build/lock_api-39921d1064022982/rustcSKwHse/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/lock_api-39921d1064022982",
          "kind": "object",
          "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.4ij5gzon61g40twsq6o3gha17.16tbq3m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/lock_api-39921d1064022982",
          "kind": "object",
          "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.59es9w9eu5d62umwllyleitqx.16tbq3m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/lock_api-39921d1064022982",
          "kind": "object",
          "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.862uo9kohh8u5a1k23gkcz3ds.16tbq3m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/lock_api-39921d1064022982",
          "kind": "object",
          "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.b2kcb936zawpjjtm05shjg7pj.16tbq3m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/lock_api-39921d1064022982",
          "kind": "object",
          "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.czzo8hmlhs3e1cpwajgs0cg5a.16tbq3m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/lock_api-39921d1064022982",
          "kind": "object",
          "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.dd260zwzyepbtjtke947ll9xk.16tbq3m.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/lock_api-39921d1064022982",
          "kind": "object",
          "path": "/target/debug/build/lock_api-39921d1064022982/build_script_build-39921d1064022982.actsr964vzz6j2k12s4b0tgrn.16tbq3m.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-30235-1783992705326601512.map",
      "pid": 30235,
      "ppid": 30151,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-30235-1783992705326601512.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
      "parsed_event_count": 371,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 373,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "x-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-gfp_p384.o /tmp/cc1w7Gg7.s\n2.090   riscv64-linux-g  30897  30722    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align ...\n2.091   powerpc64le-lin  30898  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.092   cc1              30900  30898    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/bn/montgomery.c -msecure-plt -quiet -dumpbase montgomery.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery.o ...\n2.092   cc1              30899  30897    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -imultilib . -imultiarch riscv64-linux-gnu -dD -D NDEBUG /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/limbs/limbs.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/ -dumpbase aaa1ba3e455ee2e1-limbs.c -dumpbase-ext ...\n2.102   aarch64-linux-g  30901  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.104   cc1              30902  30901    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/fipsmodule/ec/p256.c -quiet -dumpbase p256.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256.o -gdwarf-4 ...\n2.111   as               30903  30898    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery.o /tmp/cc315ypx.s\n2.118   as               30904  30901    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256.o /tmp/ccXIvgBL.s\n2.119   as               30906  30897    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/aaa1ba3e455ee2e1-limbs.o /tmp/ccEPZcuf.s\n2.120   powerpc64le-lin  30905  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.122   cc1              30907  30905    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/bn/montgomery_inv.c -msecure-plt -quiet -dumpbase montgomery_inv.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery_inv.o ...\n2.128   riscv64-linux-g  30908  30722    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align ...\n2.130   cc1              30910  30908    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -imultilib . -imultiarch riscv64-linux-gnu -dD -D NDEBUG /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/mem.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/ -dumpbase a4019cc0736b0423-mem.c -dumpbase-ext ...\n2.132   aarch64-linux-g  30909  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.134   cc1              30911  30909    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/limbs/limbs.c -quiet -dumpbase limbs.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/aaa1ba3e455ee2e1-limbs.o -gdwarf-4 ...\n2.138   as               30912  30905    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery_inv.o /tmp/ccAPijB5.s\n2.144   as               30913  30908    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a4019cc0736b0423-mem.o /tmp/cctdf2Dr.s\n2.147   powerpc64le-lin  30914  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.149   cc1              30915  30914    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/ec/ecp_nistz.c -msecure-plt -quiet -dumpbase ecp_nistz.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-ecp_nistz.o ...\n2.152   riscv64-linux-g  30916  30722    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align ...\n2.154   cc1              30917  30916    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -imultilib . -imultiarch riscv64-linux-gnu -dD -D NDEBUG /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/poly1305/poly1305.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/ -dumpbase d5a9841f3dc6e253-poly1305.c -dumpbase-ext ...\n2.163   as               30918  30909    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/aaa1ba3e455ee2e1-limbs.o /tmp/ccUoUlBo.s\n2.165   as               30919  30914    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-ecp_nistz.o /tmp/ccD4VS8K.s\n2.174   powerpc64le-lin  30920  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.176   cc1              30921  30920    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/ec/gfp_p256.c -msecure-plt -quiet -dumpbase gfp_p256.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p256.o ...\n2.177   as               30923  30916    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/d5a9841f3dc6e253-poly1305.o /tmp/ccX8WPKW.s\n2.179   aarch64-linux-g  30922  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.181   cc1              30924  30922    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/mem.c -quiet -dumpbase mem.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-mem.o -gdwarf-4 ...\n2.187   riscv64-linux-g  30925  30722    0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/libring_core_0_17_14_.a /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/25ac62e5b3c53843-curve25519.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/0bbbd18bda93c05b-aes_nohw.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/00c879ee3285a50d-montgomery.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/00c879ee3285a50d-montgomery_inv.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a0330e891e733f4e-ecp_nistz.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a0330e891e733f4e-gfp_p256.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a0330e891e733f4e-gfp_p384.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a0330e891e733f4e-p256.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/aaa1ba3e455ee2e1-limbs.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a4019cc0736b0423-mem.o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/d5a9841f3dc6e253-poly1305.o\n2.193   as               30926  30920    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p256.o /tmp/ccjuXbIe.s\n2.198   as               30927  30922    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-mem.o /tmp/ccdrLoKn.s\n2.203   powerpc64le-lin  30928  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.205   cc1              30929  30928    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/ec/gfp_p384.c -msecure-plt -quiet -dumpbase gfp_p384.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p384.o ...\n2.213   aarch64-linux-g  30930  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.215   cc1              30931  30930    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/poly1305/poly1305.c -quiet -dumpbase poly1305.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/d5a9841f3dc6e253-poly1305.o -gdwarf-4 ...\n2.234   riscv64-linux-g  30932  30722    0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/libring_core_0_17_14_.a\n2.239   as               30933  30930    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/d5a9841f3dc6e253-poly1305.o /tmp/ccCGPFfZ.s\n2.244   as               30934  30928    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p384.o /tmp/ccwrjzfQ.s\n2.254   aarch64-linux-g  30935  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.255   cc1              30937  30935    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/fipsmodule/ec/p256-nistz.c -quiet -dumpbase p256-nistz.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256-nistz.o -gdwarf-4 ...\n2.257   powerpc64le-lin  30936  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.258   cc1              30938  30936    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/fipsmodule/ec/p256.c -msecure-plt -quiet -dumpbase p256.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-p256.o ...\n2.261   riscv64-linux-g  30939  30722    0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/13067934521883617256detect_compiler_family.c\n2.263   cc1              30940  30939    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/13067934521883617256detect_compiler_family.c -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 13067934521883617256detect_compiler_family.c -dumpbase-ext .c\n2.269   riscv64-linux-g  30941  30722    0 /usr/bin/riscv64-linux-gnu-gcc -?\n2.274   riscv64-linux-g  30942  30722    0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align ...\n2.276   cc1              30943  30942    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated -imultilib . -imultiarch riscv64-linux-gnu -dD -D NDEBUG /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/crypto/constant_time_test.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/ -dumpbase a4019cc0736b0423-constant_time_test.c -dumpbase-ext ...\n2.296   as               30944  30942    0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/include -I /tmp/crate-build-riscv64-8d34af21/src/ring-0.17.14/pregenerated --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a4019cc0736b0423-constant_time_test.o /tmp/ccruuUYq.s\n2.303   riscv64-linux-g  30945  30722    0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/libring_core_0_17_14__test.a /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/a4019cc0736b0423-constant_time_test.o\n2.314   as               30946  30936    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-p256.o /tmp/ccTiUGVs.s\n2.321   riscv64-linux-g  30947  30722    0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/ring-fb98afceca4bb178/out/libring_core_0_17_14__test.a\n2.327   powerpc64le-lin  30948  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.329   cc1              30949  30948    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/limbs/limbs.c -msecure-plt -quiet -dumpbase limbs.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/aaa1ba3e455ee2e1-limbs.o ...\n2.344   rustc            30951  28923    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ring --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"dev_urandom_fallback\" ...\n2.355   runc             30955  3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process2723051921 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n2.357   as               30959  30948    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/aaa1ba3e455ee2e1-limbs.o /tmp/cchhnp2l.s\n2.362   exe              30963  30955    0 /proc/self/exe init\n2.368   powerpc64le-lin  30966  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.370   cc1              30972  30966    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/mem.c -msecure-plt -quiet -dumpbase mem.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-mem.o ...\n2.384   etcdctl          30965  30955    0 /usr/local/bin/etcdctl endpoint health\n2.385   as               30973  30966    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-mem.o /tmp/ccBgQASJ.s\n2.387   as               30974  30935    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256-nistz.o /tmp/ccSS8VRk.s\n2.394   powerpc64le-lin  30983  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.397   cc1              30984  30983    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/poly1305/poly1305.c -msecure-plt -quiet -dumpbase poly1305.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/d5a9841f3dc6e253-poly1305.o ...\n2.408   aarch64-linux-g  30985  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.410   cc1              30986  30985    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/chacha-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.416   as               30987  30985    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-chacha-armv8-linux64.o /tmp/ccmYUWl8.s\n2.422   as               30988  30983    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/d5a9841f3dc6e253-poly1305.o /tmp/cceG20FZ.s\n2.429   aarch64-linux-g  30989  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.431   cc1              30991  30989    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/chacha20_poly1305_armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.432   powerpc64le-lin  30990  30855    0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/libring_core_0_17_14_.a /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/25ac62e5b3c53843-curve25519.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/0bbbd18bda93c05b-aes_nohw.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/00c879ee3285a50d-montgomery_inv.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-ecp_nistz.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p256.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-gfp_p384.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a0330e891e733f4e-p256.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/aaa1ba3e455ee2e1-limbs.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-mem.o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/d5a9841f3dc6e253-poly1305.o\n2.438   as               30992  30989    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-chacha20_poly1305_armv8-linux64.o /tmp/ccTOii5p.s\n2.439   powerpc64le-lin  30993  30855    0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/libring_core_0_17_14_.a\n2.445   powerpc64le-lin  30994  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/7603557205145803586detect_compiler_family.c\n2.446   cc1              30995  30994    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/7603557205145803586detect_compiler_family.c -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n2.451   powerpc64le-lin  30996  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n2.454   aarch64-linux-g  30997  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.456   powerpc64le-lin  30998  30855    0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -m64 -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual ...\n2.457   cc1              30999  30997    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/aesv8-armx-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.458   cc1              31000  30998    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -imultiarch powerpc64le-linux-gnu -dD -D NDEBUG /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/crypto/constant_time_test.c -msecure-plt -quiet -dumpbase constant_time_test.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-constant_time_test.o ...\n2.463   as               31001  30997    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-aesv8-armx-linux64.o /tmp/ccckEXz1.s\n2.474   aarch64-linux-g  31002  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.476   cc1              31003  31002    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/aesv8-gcm-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.481   as               31004  30998    0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/include -I /tmp/crate-build-ppc64le-edc2v6gi/src/ring-0.17.14/pregenerated -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-constant_time_test.o /tmp/ccoNgP15.s\n2.482   as               31005  31002    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-aesv8-gcm-armv8-linux64.o /tmp/ccpOuwXq.s\n2.491   powerpc64le-lin  31006  30855    0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/libring_core_0_17_14__test.a /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/a4019cc0736b0423-constant_time_test.o\n2.493   powerpc64le-lin  31007  30855    0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/ring-f1cd240d23a284c9/out/libring_core_0_17_14__test.a\n2.495   aarch64-linux-g  31008  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.497   cc1              31009  31008    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/ghash-neon-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.501   rustc            31011  29208    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ring --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"dev_urandom_fallback\" ...\n2.503   as               31012  31008    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-ghash-neon-armv8-linux64.o /tmp/ccoJfkJQ.s\n2.514   aarch64-linux-g  31016  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.516   cc1              31017  31016    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/ghashv8-armx-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.522   as               31018  31016    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-ghashv8-armx-linux64.o /tmp/ccRCniPs.s\n2.534   aarch64-linux-g  31019  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.535   cc1              31020  31019    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/vpaes-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.542   as               31021  31019    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-vpaes-armv8-linux64.o /tmp/cc2DbBjJ.s\n2.553   aarch64-linux-g  31022  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.555   cc1              31023  31022    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/armv8-mont-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.562   as               31024  31022    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-armv8-mont-linux64.o /tmp/cckUevwX.s\n2.574   aarch64-linux-g  31025  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.576   cc1              31026  31025    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/p256-armv8-asm-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.583   as               31027  31025    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-p256-armv8-asm-linux64.o /tmp/ccYYbLjb.s\n2.596   aarch64-linux-g  31028  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.599   cc1              31029  31028    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/sha512-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.604   as               31030  31028    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-sha512-armv8-linux64.o /tmp/ccDnB7Gq.s\n2.617   aarch64-linux-g  31031  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.618   cc1              31032  31031    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -lang-asm -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated/sha256-armv8-linux64.S -mlittle-endian -mabi=lp64 -std=c11 -Wextra -Wall -Wbad-function-cast ...\n2.625   as               31033  31031    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as --gdwarf2 -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-sha256-armv8-linux64.o /tmp/ccQIagMC.s\n2.638   aarch64-linux-g  31034  30748    0 /usr/bin/aarch64-linux-gnu-ar cq /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/libring_core_0_17_14_.a /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/25ac62e5b3c53843-curve25519.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/0bbbd18bda93c05b-aes_nohw.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/00c879ee3285a50d-montgomery.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/00c879ee3285a50d-montgomery_inv.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-ecp_nistz.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-gfp_p256.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-gfp_p384.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/aaa1ba3e455ee2e1-limbs.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-mem.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/d5a9841f3dc6e253-poly1305.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a0330e891e733f4e-p256-nistz.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-chacha-armv8-linux64.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-chacha20_poly1305_armv8-linux64.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-aesv8-armx-linux64.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-aesv8-gcm-armv8-linux64.o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/c322a0bcc369f531-ghash-neon-armv8-linux64.o ...\n2.647   aarch64-linux-g  31035  30748    0 /usr/bin/aarch64-linux-gnu-ar s /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/libring_core_0_17_14_.a\n2.655   aarch64-linux-g  31036  30748    0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/7011150007031298944detect_compiler_family.c\n2.656   cc1              31037  31036    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/7011150007031298944detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n2.661   aarch64-linux-g  31038  30748    0 /usr/bin/aarch64-linux-gnu-gcc -?\n2.665   aarch64-linux-g  31039  30748    0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -Wall -Wextra -fvisibility=hidden -std=c1x -Wall -Wbad-function-cast -Wcast-align -Wcast-qual -Wconversion ...\n2.667   cc1              31040  31039    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -imultiarch aarch64-linux-gnu -dD -D NDEBUG /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/crypto/constant_time_test.c -quiet -dumpbase constant_time_test.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-constant_time_test.o -gdwarf-4 ...\n2.690   as               31041  31039    0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/include -I /tmp/crate-build-aarch64-s6wg4hei/src/ring-0.17.14/pregenerated -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-constant_time_test.o /tmp/ccxoI22b.s\n2.704   aarch64-linux-g  31042  30748    0 /usr/bin/aarch64-linux-gnu-ar cq /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/libring_core_0_17_14__test.a /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/a4019cc0736b0423-constant_time_test.o\n2.707   aarch64-linux-g  31043  30748    0 /usr/bin/aarch64-linux-gnu-ar s /target/aarch64-unknown-linux-gnu/debug/build/ring-cc8314ad93c6a068/out/libring_core_0_17_14__test.a\n2.715   rustc            31045  29032    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ring --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"dev_urandom_fallback\" ...\n4.030   git              31817  2235138   0 /usr/bin/git config --get commit.template\n4.046   git              31818  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n4.061   git              31819  2235138   0 /usr/bin/git status -z -uall\n4.076   git              31820  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n4.272   sh               31821  2147557   0 /bin/sh -c which ps\n4.274   which            31821  2147557   0 /usr/bin/which ps\n4.276   sh               31822  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n4.277   ps               31822  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n4.300   sh               31823  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n4.302   cpuUsage.sh      31823  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n4.303   sed              31824  31823    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n4.305   cat              31825  31823    0 /usr/bin/cat /proc/2240539/stat\n4.307   cat              31826  31823    0 /usr/bin/cat /proc/4193716/stat\n4.308   sleep            31827  31823    0 /usr/bin/sleep 1\n4.521   git              31829  2235138   0 /usr/bin/git worktree list --porcelain\n5.310   sed              31830  31823    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n5.312   cat              31831  31823    0 /usr/bin/cat /proc/2240539/stat\n5.314   cat              31833  31823    0 /usr/bin/cat /proc/4193716/stat\n5.383   16               31835  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n5.401   frpc             31835  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n9.099   git              31842  2235138   0 /usr/bin/git config --get commit.template\n9.118   git              31843  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n9.139   git              31844  2235138   0 /usr/bin/git status -z -uall\n9.159   git              31845  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n14.907  runc             31847  4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process791607860 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n14.913  exe              31854  31847    0 /proc/self/exe init\n14.934  curl             31856  31847    0 /usr/bin/curl -f http://localhost:9091/healthz\n15.897  runc             31866  25919    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5 --log-format json --systemd-cgroup kill --all 6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5a0adf 9\n15.906  runc             31872  25919    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5 --log-format json --systemd-cgroup delete 6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5a0adf\n16.071  containerd-shim  31878  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5a0adf -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5 delete\n16.074  runc             31885  31878    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5a0ad --log-format json delete --force 6c901a2b43672a4e748d351cc895b81659504ee03674c0815b2887ecfe5a0adf\n16.126  sh               31894  31890    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth8d33afa\n16.128  sed              31896  31894    0 /usr/bin/sed -n s/^driver: //p\n16.128  ethtool          31895  31894    0 /usr/sbin/ethtool -i veth8d33afa\n16.136  systemd-sysctl   31899  31890    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8d33afa --prefix=/net/ipv4/neigh/veth8d33afa --prefix=/net/ipv6/conf/veth8d33afa --prefix=/net/ipv6/neigh/veth8d33afa\n16.883  sh               31906  2147557   0 /bin/sh -c which ps\n16.885  which            31906  2147557   0 /usr/bin/which ps\n16.887  sh               31907  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.890  ps               31907  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.920  sh               31908  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.921  cpuUsage.sh      31908  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.923  sed              31909  31908    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.926  cat              31910  31908    0 /usr/bin/cat /proc/2240539/stat\n16.928  cat              31911  31908    0 \n16.929  sleep            31912  31908    0 /usr/bin/sleep 1\n17.114  runc             31914  27017    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1 --log-format json --systemd-cgroup kill --all aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1c2de4 9\n17.133  runc             31920  27017    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1 --log-format json --systemd-cgroup delete aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1c2de4\n17.301  git              31926  2235138   0 /usr/bin/git config --get commit.template\n17.321  git              31927  2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n17.328  containerd-shim  31928  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1c2de4 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1 delete\n17.331  runc             31935  31928    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1c2de --log-format json delete --force aa2b18261db826d9420025cf2c0688e1416e889dbde13ca8305673d5ca1c2de4\n17.342  git              31938  2235138   0 /usr/bin/git status -z -uall\n17.361  git              31941  2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n17.372  systemd-sysctl   31942  31890    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf419e17 --prefix=/net/ipv4/neigh/vethf419e17 --prefix=/net/ipv6/conf/vethf419e17 --prefix=/net/ipv6/neigh/vethf419e17\n17.627  runc             31944  27816    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83 --log-format json --systemd-cgroup kill --all af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83c5764 9\n17.647  runc             31950  27816    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83 --log-format json --systemd-cgroup delete af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83c5764\n17.836  containerd-shim  31956  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83c5764 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83 delete\n17.839  runc             31963  31956    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83c576 --log-format json delete --force af75ae9e8326be4064dbd5badd9acf52579f727326bbec90d3b09a4ac83c5764\n17.884  systemd-sysctl   31969  31943    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5033a9f --prefix=/net/ipv4/neigh/veth5033a9f --prefix=/net/ipv6/conf/veth5033a9f --prefix=/net/ipv6/neigh/veth5033a9f\n17.931  sed              31970  31908    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.934  cat              31971  31908    0 /usr/bin/cat /proc/2240539/stat\n17.936  cat              31973  31908    0 /usr/bin/cat /proc/4193716/stat\n17.960  runc             31975  25626    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5016ad3988b64adfc45e2f6872bf60289eaeaf4e4fd40b1739c81a92de5 --log-format json --systemd-cgroup kill --all 5016ad3988b64adfc45e2f6872bf60289eaeaf4e4fd40b1739c81a92de58d1ec 9\n17.968  runc             31981  28208    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f0 --log-format json --systemd-cgroup kill --all 96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f045866 9\n17.977  runc             31988  28208    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f0 --log-format json --systemd-cgroup delete 96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f045866\n17.980  runc             31994  25626    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5016ad3988b64adfc45e2f6872bf60289eaeaf4e4fd40b1739c81a92de5 --log-format json --systemd-cgroup delete 5016ad3988b64adfc45e2f6872bf60289eaeaf4e4fd40b1739c81a92de58d1ec\n18.066  runc             32000  28082    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/34a9607f36f42f3715f2bbb2bc80c9844ae22a434476eedafd85fa6c911 --log-format json --systemd-cgroup kill --all 34a9607f36f42f3715f2bbb2bc80c9844ae22a434476eedafd85fa6c911ba296 9\n18.074  runc             32006  28082    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/34a9607f36f42f3715f2bbb2bc80c9844ae22a434476eedafd85fa6c911 --log-format json --systemd-cgroup delete 34a9607f36f42f3715f2bbb2bc80c9844ae22a434476eedafd85fa6c911ba296\n18.114  runc             32013  27492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b0980f18dae85a9701abc50dcde6ee99e938103ccdbfb553dde921ae73d --log-format json --systemd-cgroup kill --all b0980f18dae85a9701abc50dcde6ee99e938103ccdbfb553dde921ae73d03fbc 9\n18.122  runc             32019  27492    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b0980f18dae85a9701abc50dcde6ee99e938103ccdbfb553dde921ae73d --log-format json --systemd-cgroup delete b0980f18dae85a9701abc50dcde6ee99e938103ccdbfb553dde921ae73d03fbc\n18.195  containerd-shim  32025  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f045866 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f0 delete\n18.197  runc             32030  28291    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/67fa9a024237996e4049d5cfcbf2f5183367331030b1d2499d22df7973b --log-format json --systemd-cgroup kill --all 67fa9a024237996e4049d5cfcbf2f5183367331030b1d2499d22df7973b8b760 9\n18.198  runc             32039  32025    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f04586 --log-format json delete --force 96ed02514c169c3b1de891e52418e56763003c5785bf656539e6426c8f045866\n18.205  runc             32044  28291    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/67fa9a024237996e4049d5cfcbf2f5183367331030b1d2499d22df7973b --log-format json --systemd-cgroup delete 67fa9a024237996e4049d5cfcbf2f5183367331030b1d2499d22df7973b8b760\n18.251  systemd-sysctl   32050  31943    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth41b3fe5 --prefix=/net/ipv4/neigh/veth41b3fe5 --prefix=/net/ipv6/conf/veth41b3fe5 --prefix=/net/ipv6/neigh/veth41b3fe5\n"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 30353,
      "build_script_target_dir": "lock_api-39921d1064022982",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 30355,
      "ppid": 30353,
      "root_cargo_pid": 29713,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/lock_api-39921d1064022982/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 30353,
      "build_script_target_dir": "lock_api-39921d1064022982",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/lock_api-39921d1064022982/build-script-build",
      "pid": 30353,
      "ppid": 29713,
      "root_cargo_pid": 29713,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_0a36ac03abfe7b95_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/lock_api-6a1572496f12bfd4/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 30353,
      "build_script_target_dir": "lock_api-39921d1064022982",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 30378,
      "ppid": 30353,
      "root_cargo_pid": 29713,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "lock_api",
      "cwd": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "event_id": "bsrun:46bf16e519a33b29:00d165f8f4401f24:e8ac304c4608595a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/lock_api-39921d1064022982/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
      "out_dir": "/target/debug/build/lock_api-39921d1064022982/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
      "success": true,
      "target": null,
      "version": "0.4.12",
      "_owner": {
        "crate": "lock_api",
        "version": "0.4.12",
        "package_id": "path+file:///tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12#lock_api@0.4.12",
        "manifest_dir": "/tmp/crate-build-riscv64-3p44xzrj/src/lock_api-0.4.12",
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
      "build_script_root_pid": 30353,
      "build_script_target_dir": "lock_api-39921d1064022982",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 30355,
      "ppid": 30353,
      "root_cargo_pid": 29713,
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
        "autocfg_0a36ac03abfe7b95_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/lock_api-6a1572496f12bfd4/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 30353,
      "build_script_target_dir": "lock_api-39921d1064022982",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 30378,
      "ppid": 30353,
      "root_cargo_pid": 29713,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 142,
    "crate": "lock_api",
    "version": "0.4.12",
    "crate_id": "69133",
    "version_id": "1126551",
    "downloads": 162902095,
    "cumulative_downloads": 35045006455,
    "cumulative_share_of_global": 0.13102518879171218,
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
