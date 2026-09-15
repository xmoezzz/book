# `substring` `1.4.5`

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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
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
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE",
    "/target/debug/build/substring-049b5fca247331ec",
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
      "directory": "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-462684-1783994521960686334.map",
  "pid": 462684,
  "ppid": 462657,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-462684-1783994521960686334.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "workspace_root": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5"
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
      "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
      "name": "substring",
      "version": "1.4.5",
      "manifest_path": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5"
    }
  ],
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 462684,
  "ppid": 462657,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "substring",
  "cargo_pkg_version": "1.4.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "event_id": "used:cc:895386976ebd4d72:d33f927785193282:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
  "pid": 462684,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "substring",
  "cargo_pkg_version": "1.4.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "event_id": "used:cc:895386976ebd4d72:d2906925fdbf4377:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
  "pid": 462684,
  "sha256": "921f32040fb78cca73e8ab36322ba0c388763d2020795c7df085d6f22e9daeb5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "substring",
  "cargo_pkg_version": "1.4.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "event_id": "used:cc:895386976ebd4d72:3242658807b6e643:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
  "pid": 462684,
  "sha256": "36f4698a76fa74042ef103a8bc080cae97f5dac740544b6c53b4d2649a3448e9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "substring",
  "cargo_pkg_version": "1.4.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "event_id": "used:cc:895386976ebd4d72:077f4babc6394f19:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
  "pid": 462684,
  "sha256": "b932fe0be511ff0200f4f2983bed405b65dd4ac56e275106fa97e20d562cd675",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "substring",
  "cargo_pkg_version": "1.4.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "event_id": "used:cc:895386976ebd4d72:9e1e9d489d17a35c:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
  "pid": 462684,
  "sha256": "016b0fec60a96d6a2fc5ef5910fc00124cd6be55ab19b134ecfebea345948b31",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "substring",
  "cargo_pkg_version": "1.4.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "event_id": "used:cc:895386976ebd4d72:da08c906208e8d18:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
  "pid": 462684,
  "sha256": "4c03471e71c5f23229d59fe12a54616a2e09882c67082fc7950c93d7294e38a9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "substring",
  "cargo_pkg_version": "1.4.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "event_id": "used:cc:895386976ebd4d72:75ee6d0f2852661f:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
  "pid": 462684,
  "sha256": "fef839a40b37fde68d6749a1767745534a9dcce814d20139fce2047d9590b58a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
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
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "cargo_pkg_name": "substring",
  "cargo_pkg_version": "1.4.5",
  "context_path": "/tmp/native-trace-461198-1783994517273/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-461198-1783994517273/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 462684,
  "ppid": 462657,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE",
    "/target/debug/build/substring-049b5fca247331ec",
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
      "directory": "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-462684-1783994521960686334.map",
  "pid": 462684,
  "ppid": 462657,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-462684-1783994521960686334.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
  "parse_error_count": 2,
  "parsed_event_count": 1223,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1225,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o -c brotli/enc/block_splitter.c\n12.948  cc1              467426 467425   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/block_splitter.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-block_splitter.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n12.954  powerpc64le-lin  467427 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o -c brotli/enc/brotli_bit_stream.c\n12.956  cc1              467428 467427   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/brotli_bit_stream.c -msecure-plt -quiet -dumpbase brotli_bit_stream.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.058  as               467433 467425   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o /tmp/cc0wabID.s\n13.078  as               467435 467427   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o /tmp/ccDRmlLO.s\n13.081  riscv64-linux-g  467436 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o -c brotli/enc/brotli_bit_stream.c\n13.083  cc1              467437 467436   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/brotli_bit_stream.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-brotli_bit_stream.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.097  powerpc64le-lin  467439 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o -c brotli/enc/cluster.c\n13.099  cc1              467440 467439   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/cluster.c -msecure-plt -quiet -dumpbase cluster.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.166  as               467444 467439   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o /tmp/ccYalp1H.s\n13.177  powerpc64le-lin  467445 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o -c brotli/enc/compress_fragment.c\n13.179  cc1              467446 467445   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/compress_fragment.c -msecure-plt -quiet -dumpbase compress_fragment.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.219  as               467447 467436   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o /tmp/ccLsJJqy.s\n13.248  riscv64-linux-g  467448 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o -c brotli/enc/cluster.c\n13.249  cc1              467449 467448   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/cluster.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-cluster.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.314  as               467450 467448   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o /tmp/cc6fZGYO.s\n13.329  riscv64-linux-g  467451 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o -c brotli/enc/compress_fragment.c\n13.331  cc1              467452 467451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/compress_fragment.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-compress_fragment.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.369  as               467453 467445   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o /tmp/ccQBGv8d.s\n13.394  powerpc64le-lin  467454 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o -c brotli/enc/compress_fragment_two_pass.c\n13.396  cc1              467455 467454   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/compress_fragment_two_pass.c -msecure-plt -quiet -dumpbase compress_fragment_two_pass.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.585  as               467456 467454   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o /tmp/ccWkXESU.s\n13.612  powerpc64le-lin  467457 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o -c brotli/enc/dictionary_hash.c\n13.613  cc1              467458 467457   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/dictionary_hash.c -msecure-plt -quiet -dumpbase dictionary_hash.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.621  as               467459 467451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o /tmp/ccHNIzEC.s\n13.648  as               467460 467457   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o /tmp/ccjKOVx6.s\n13.660  powerpc64le-lin  467461 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o -c brotli/enc/encode.c\n13.662  cc1              467462 467461   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/encode.c -msecure-plt -quiet -dumpbase encode.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.688  riscv64-linux-g  467463 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o -c brotli/enc/compress_fragment_two_pass.c\n13.690  cc1              467464 467463   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/compress_fragment_two_pass.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-compress_fragment_two_pass.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.866  as               467465 467461   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o /tmp/ccD4wouo.s\n13.889  as               467466 467463   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o /tmp/cc7wI7An.s\n13.890  powerpc64le-lin  467467 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o -c brotli/enc/entropy_encode.c\n13.892  cc1              467468 467467   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/entropy_encode.c -msecure-plt -quiet -dumpbase entropy_encode.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.920  as               467469 467467   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o /tmp/ccUwGNES.s\n13.929  powerpc64le-lin  467470 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o -c brotli/enc/histogram.c\n13.931  cc1              467471 467470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/histogram.c -msecure-plt -quiet -dumpbase histogram.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.944  riscv64-linux-g  467472 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o -c brotli/enc/dictionary_hash.c\n13.945  cc1              467473 467472   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/dictionary_hash.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-dictionary_hash.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.956  as               467474 467470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o /tmp/ccdplC63.s\n13.964  powerpc64le-lin  467475 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o -c brotli/enc/literal_cost.c\n13.965  cc1              467476 467475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/literal_cost.c -msecure-plt -quiet -dumpbase literal_cost.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.981  as               467477 467472   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o /tmp/cc6vLa2U.s\n13.990  as               467479 467475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o /tmp/ccPiYVat.s\n13.991  riscv64-linux-g  467478 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o -c brotli/enc/encode.c\n13.992  cc1              467480 467478   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/encode.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-encode.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.998  powerpc64le-lin  467481 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o -c brotli/enc/memory.c\n14.000  cc1              467482 467481   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/memory.c -msecure-plt -quiet -dumpbase memory.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n14.018  as               467483 467481   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o /tmp/ccccrRdU.s\n14.025  powerpc64le-lin  467484 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o -c brotli/enc/metablock.c\n14.027  cc1              467485 467484   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/metablock.c -msecure-plt -quiet -dumpbase metablock.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n14.103  as               467486 467484   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o /tmp/ccFnMr38.s\n14.116  powerpc64le-lin  467487 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o -c brotli/enc/static_dict.c\n14.118  cc1              467488 467487   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/static_dict.c -msecure-plt -quiet -dumpbase static_dict.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n14.221  as               467489 467478   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o /tmp/ccqDvI7W.s\n14.270  riscv64-linux-g  467490 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o -c brotli/enc/entropy_encode.c\n14.272  cc1              467491 467490   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/entropy_encode.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-entropy_encode.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.297  as               467492 467487   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o /tmp/cc2XVbsl.s\n14.298  as               467493 467490   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o /tmp/ccHomo7A.s\n14.306  riscv64-linux-g  467494 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o -c brotli/enc/histogram.c\n14.307  cc1              467495 467494   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/histogram.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-histogram.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.329  powerpc64le-lin  467496 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o -c brotli/enc/utf8_util.c\n14.330  cc1              467497 467496   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/utf8_util.c -msecure-plt -quiet -dumpbase utf8_util.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n14.332  as               467498 467494   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o /tmp/ccZvcoqW.s\n14.338  riscv64-linux-g  467499 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o -c brotli/enc/literal_cost.c\n14.340  cc1              467500 467499   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/literal_cost.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-literal_cost.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.346  as               467501 467496   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o /tmp/cc5uSpe5.s\n14.354  powerpc64le-lin  467502 467309   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o ...\n14.362  powerpc64le-lin  467503 467309   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a\n14.367  as               467504 467499   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o /tmp/ccH4vY28.s\n14.373  riscv64-linux-g  467507 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o -c brotli/enc/memory.c\n14.374  rustc            467506 466544   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name brotli_sys --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c79f4d53b620c131 ...\n14.375  cc1              467508 467507   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/memory.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-memory.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.390  as               467512 467507   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o /tmp/cc1l9i2A.s\n14.395  riscv64-linux-g  467513 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o -c brotli/enc/metablock.c\n14.397  cc1              467514 467513   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/metablock.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-metablock.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.476  as               467518 467513   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o /tmp/ccRXWm55.s\n14.496  riscv64-linux-g  467519 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o -c brotli/enc/static_dict.c\n14.498  cc1              467520 467519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/static_dict.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-static_dict.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.690  as               467521 467519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o /tmp/ccSLUSwl.s\n14.727  riscv64-linux-g  467522 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o -c brotli/enc/utf8_util.c\n14.728  cc1              467523 467522   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/utf8_util.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-utf8_util.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.740  as               467524 467522   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o /tmp/ccuTSl42.s\n14.746  riscv64-linux-g  467525 467213   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o ...\n14.783  riscv64-linux-g  467526 467213   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a\n14.826  rustc            467528 466421   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name brotli_sys --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28a7a4aa9eb732c2 ...\n15.471  cross            467535 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.472  rustc            467538 467535   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.477  rustc            467538 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.484  cross            467548 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n15.486  rustc            467553 467548   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.489  rustc            467562 467535   0 /home/xmoe/.cargo/bin/rustc -vV\n15.491  rustc            467553 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.494  rustc            467562 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.502  cargo            467575 467535   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.503  rustc            467576 467548   0 /home/xmoe/.cargo/bin/rustc -vV\n15.507  cargo            467575 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.509  rustc            467576 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.518  rustc            467595 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.518  cargo            467594 467548   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.523  cargo            467594 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.527  rustc            467605 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.533  rustc            467606 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.540  rustc            467610 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.542  rustc            467612 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.552  rustc            467619 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.554  rustc            467620 467535   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.559  rustc            467620 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.567  rustc            467635 467548   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.570  docker           467644 467535   0 /usr/bin/docker --help\n15.572  rustc            467635 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.583  docker           467660 467535   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.584  docker           467661 467548   0 /usr/bin/docker --help\n15.594  docker           467682 467548   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.595  runc             467683 1599     0 /usr/bin/runc --version\n15.598  docker-init      467694 1599     0 /usr/bin/docker-init --version\n15.599  docker           467695 467535   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.607  runc             467711 1599     0 /usr/bin/runc --version\n15.610  docker-init      467717 1599     0 /usr/bin/docker-init --version\n15.612  docker           467719 467548   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.612  runc             467722 1599     0 /usr/bin/runc --version\n15.615  docker-init      467733 1599     0 /usr/bin/docker-init --version\n15.623  runc             467739 1599     0 /usr/bin/runc --version\n15.627  docker-init      467745 1599     0 /usr/bin/docker-init --version\n15.636  rustup           467748 467535   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.642  rustup           467757 467535   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.650  rustup           467766 467548   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.656  rustup           467775 467548   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.665  rustup           467784 467535   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.680  rustup           467793 467548   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.689  uname            467802 467535   0 /usr/bin/uname -r\n15.703  uname            467803 467548   0 /usr/bin/uname -r\n15.707  docker           467804 467535   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.720  docker           467814 467548   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.755  systemd-sysctl   467830 467828   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha60e121 --prefix=/net/ipv4/neigh/vetha60e121 --prefix=/net/ipv6/conf/vetha60e121 --prefix=/net/ipv6/neigh/vetha60e121\n15.757  systemd-sysctl   467831 467829   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5d6981e --prefix=/net/ipv4/neigh/veth5d6981e --prefix=/net/ipv6/conf/veth5d6981e --prefix=/net/ipv6/neigh/veth5d6981e\n15.773  containerd-shim  467867 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee start\n15.774  systemd-sysctl   467866 467842   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth00063ae --prefix=/net/ipv4/neigh/veth00063ae --prefix=/net/ipv6/conf/veth00063ae --prefix=/net/ipv6/neigh/veth00063ae\n15.776  systemd-sysctl   467871 467853   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth40e6fa1 --prefix=/net/ipv4/neigh/veth40e6fa1 --prefix=/net/ipv6/conf/veth40e6fa1 --prefix=/net/ipv6/neigh/veth40e6fa1\n15.778  containerd-shim  467875 467867   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee -address /var/run/docker/containerd/containerd.sock\n15.781  runc             467884 467875   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee\n15.786  containerd-shim  467890 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 start\n15.790  exe              467899 467884   0 \n15.791  containerd-shim  467900 467890   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 -address /var/run/docker/containerd/containerd.sock\n15.794  runc             467912 467900   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490\n15.800  exe              467920 467912   0 /proc/self/exe init\n15.825  exe              467936 467884   0 /proc/1599/exe -exec-root=/var/run/docker a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee d7da31e8f8e1\n15.826  exe              467937 467912   0 /proc/1599/exe -exec-root=/var/run/docker 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 d7da31e8f8e1\n15.845  exe              467952 1599     0 /proc/self/exe /var/run/docker/netns/67593d8830ed all false\n15.846  exe              467953 1599     0 /proc/self/exe /var/run/docker/netns/3c05773b9ce6 all false\n16.045  runc             467990 467900   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --log-format json --systemd-cgroup start 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490\n16.046  runc             467991 467875   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --log-format json --systemd-cgroup start a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee\n16.051  sh               467930 467900   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.052  sh               467923 467875   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.052  cargo            468002 467930   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.054  cargo            468003 467923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.063  cargo-native-tr  468003 467923   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.063  cargo-native-tr  468002 467930   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.067  cargo            468004 468003   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.067  cargo            468005 468002   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.078  rustc            468006 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.078  rustc            468007 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.089  rustc            468010 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.090  rustc            468011 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.104  execsnoop        468018 468002   0 /usr/local/bin/execsnoop -t\n16.104  python3          468018 468002   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.104  execsnoop        468021 468003   0 /usr/local/bin/execsnoop -t\n16.105  python3          468021 468003   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.599  runc             468024 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2801572281 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n16.605  exe              468031 468024   0 /proc/self/exe init\n16.622  curl             468034 468024   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n16.855  sh               468040 2147557   0 /bin/sh -c which ps\n16.857  which            468040 2147557   0 /usr/bin/which ps\n16.859  sh               468041 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.860  ps               468041 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.887  sh               468042 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.889  cpuUsage.sh      468042 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.890  sed              468043 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.892  cat              468044 468042   0 /usr/bin/cat /proc/2240539/stat\n16.894  cat              468045 468042   0 /usr/bin/cat /proc/4193716/stat\n16.895  sleep            468046 468042   0 /usr/bin/sleep 1\n17.897  sed              468047 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.899  cat              468048 468042   0 /usr/bin/cat /proc/2240539/stat\n17.901  cat              468050 468042   0 /usr/bin/cat /proc/4193716/stat\n17.969  cargo            468052 468002   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.982  rustc            468053 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.000  rustc            468059 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n18.043  cc               468079 468059   0 /tmp/native-trace-468002-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.045  cc               468080 468079   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.048  collect2         468081 468080   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.049  ld.lld           468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n18.050  rust-lld         468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.086  build-script-bu  468100 468052   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n18.092  rustc            468102 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=01dbfa75f86e934e ...\n18.240  cargo            468109 468003   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.253  rustc            468110 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.272  rustc            468116 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n18.294  runc             468120 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup kill --all c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 9\n18.312  runc             468143 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup delete c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n18.313  cc               468142 468116   0 /tmp/native-trace-468003-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.315  cc               468149 468142   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.317  collect2         468150 468149   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.319  ld.lld           468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n18.321  rust-lld         468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.365  build-script-bu  468169 468109   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n18.371  rustc            468171 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=eb508d71aca425cd ...\n18.507  containerd-shim  468178 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d delete\n18.509  runc             468184 468178   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b7 --log-format json delete --force c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/substring-049b5fca247331ec/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 462826,
  "build_script_target_dir": "substring-049b5fca247331ec",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/substring-049b5fca247331ec/build-script-build",
  "pid": 462826,
  "ppid": 462470,
  "root_cargo_pid": 462470,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "_build_script_out_dir": "/target/debug/build/substring-049b5fca247331ec/out"
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
  "build_script_root_pid": 462826,
  "build_script_target_dir": "substring-049b5fca247331ec",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 462829,
  "ppid": 462826,
  "root_cargo_pid": 462470,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "_build_script_out_dir": "/target/debug/build/substring-049b5fca247331ec/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 17

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_abccccb438587ecf_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/substring-b7ed59fe071f9b2b/out",
    "--emit=llvm-ir",
    "--target",
    "aarch64-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 462826,
  "build_script_target_dir": "substring-049b5fca247331ec",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 462843,
  "ppid": 462826,
  "root_cargo_pid": 462470,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "_build_script_out_dir": "/target/debug/build/substring-049b5fca247331ec/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 18

```json
{
  "crate": "substring",
  "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "event_id": "bsrun:222356d3a3b01f01:bebeb726cf26c996:0b6d9a1c468b957a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/substring-049b5fca247331ec/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
  "out_dir": "/target/debug/build/substring-049b5fca247331ec/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
  "success": true,
  "target": null,
  "version": "1.4.5",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
    "source": "cwd_prefix"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 462826,
  "build_script_target_dir": "substring-049b5fca247331ec",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 462829,
  "ppid": 462826,
  "root_cargo_pid": 462470,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 20

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_abccccb438587ecf_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/substring-b7ed59fe071f9b2b/out",
    "--emit=llvm-ir",
    "--target",
    "aarch64-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 462826,
  "build_script_target_dir": "substring-049b5fca247331ec",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 462843,
  "ppid": 462826,
  "root_cargo_pid": 462470,
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
  "time": "2026-07-14T02:02:19.935900+00:00",
  "crate": "substring",
  "version": "1.4.5",
  "architecture": "aarch64",
  "duration_seconds": 28.570737263187766,
  "trace_record_count": 18,
  "trace_owner_summary": {
    "owner_package_count": 2,
    "owner_packages": [
      {
        "crate": "autocfg",
        "version": "1.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml"
      },
      {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "manifest_path": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5/Cargo.toml"
      }
    ],
    "attributed_event_count": 13,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "substring",
        "version": "1.4.5",
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
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "workspace_root": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5"
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
          "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
          "name": "substring",
          "version": "1.4.5",
          "manifest_path": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5"
        }
      ],
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 462684,
      "ppid": 462657,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "substring",
      "cargo_pkg_version": "1.4.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "event_id": "used:cc:895386976ebd4d72:d33f927785193282:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
      "pid": 462684,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "substring",
      "cargo_pkg_version": "1.4.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "event_id": "used:cc:895386976ebd4d72:d2906925fdbf4377:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
      "pid": 462684,
      "sha256": "921f32040fb78cca73e8ab36322ba0c388763d2020795c7df085d6f22e9daeb5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "substring",
      "cargo_pkg_version": "1.4.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "event_id": "used:cc:895386976ebd4d72:3242658807b6e643:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
      "pid": 462684,
      "sha256": "36f4698a76fa74042ef103a8bc080cae97f5dac740544b6c53b4d2649a3448e9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "substring",
      "cargo_pkg_version": "1.4.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "event_id": "used:cc:895386976ebd4d72:077f4babc6394f19:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
      "pid": 462684,
      "sha256": "b932fe0be511ff0200f4f2983bed405b65dd4ac56e275106fa97e20d562cd675",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "substring",
      "cargo_pkg_version": "1.4.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "event_id": "used:cc:895386976ebd4d72:9e1e9d489d17a35c:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
      "pid": 462684,
      "sha256": "016b0fec60a96d6a2fc5ef5910fc00124cd6be55ab19b134ecfebea345948b31",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "substring",
      "cargo_pkg_version": "1.4.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "event_id": "used:cc:895386976ebd4d72:da08c906208e8d18:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
      "pid": 462684,
      "sha256": "4c03471e71c5f23229d59fe12a54616a2e09882c67082fc7950c93d7294e38a9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "substring",
      "cargo_pkg_version": "1.4.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "event_id": "used:cc:895386976ebd4d72:75ee6d0f2852661f:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
      "pid": 462684,
      "sha256": "fef839a40b37fde68d6749a1767745534a9dcce814d20139fce2047d9590b58a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
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
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "cargo_pkg_name": "substring",
      "cargo_pkg_version": "1.4.5",
      "context_path": "/tmp/native-trace-461198-1783994517273/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-461198-1783994517273/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 462684,
      "ppid": 462657,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE",
        "/target/debug/build/substring-049b5fca247331ec",
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
          "directory": "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/rustc0iKitE/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.02tkgl6.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.02tkgl6.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.02tkgl6.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.02tkgl6.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.02tkgl6.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.02tkgl6.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-462684-1783994521960686334.map",
      "pid": 462684,
      "ppid": 462657,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-462684-1783994521960686334.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
      "parsed_event_count": 1223,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1225,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o -c brotli/enc/block_splitter.c\n12.948  cc1              467426 467425   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/block_splitter.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-block_splitter.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n12.954  powerpc64le-lin  467427 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o -c brotli/enc/brotli_bit_stream.c\n12.956  cc1              467428 467427   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/brotli_bit_stream.c -msecure-plt -quiet -dumpbase brotli_bit_stream.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.058  as               467433 467425   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o /tmp/cc0wabID.s\n13.078  as               467435 467427   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o /tmp/ccDRmlLO.s\n13.081  riscv64-linux-g  467436 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o -c brotli/enc/brotli_bit_stream.c\n13.083  cc1              467437 467436   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/brotli_bit_stream.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-brotli_bit_stream.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.097  powerpc64le-lin  467439 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o -c brotli/enc/cluster.c\n13.099  cc1              467440 467439   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/cluster.c -msecure-plt -quiet -dumpbase cluster.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.166  as               467444 467439   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o /tmp/ccYalp1H.s\n13.177  powerpc64le-lin  467445 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o -c brotli/enc/compress_fragment.c\n13.179  cc1              467446 467445   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/compress_fragment.c -msecure-plt -quiet -dumpbase compress_fragment.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.219  as               467447 467436   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o /tmp/ccLsJJqy.s\n13.248  riscv64-linux-g  467448 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o -c brotli/enc/cluster.c\n13.249  cc1              467449 467448   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/cluster.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-cluster.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.314  as               467450 467448   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o /tmp/cc6fZGYO.s\n13.329  riscv64-linux-g  467451 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o -c brotli/enc/compress_fragment.c\n13.331  cc1              467452 467451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/compress_fragment.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-compress_fragment.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.369  as               467453 467445   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o /tmp/ccQBGv8d.s\n13.394  powerpc64le-lin  467454 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o -c brotli/enc/compress_fragment_two_pass.c\n13.396  cc1              467455 467454   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/compress_fragment_two_pass.c -msecure-plt -quiet -dumpbase compress_fragment_two_pass.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.585  as               467456 467454   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o /tmp/ccWkXESU.s\n13.612  powerpc64le-lin  467457 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o -c brotli/enc/dictionary_hash.c\n13.613  cc1              467458 467457   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/dictionary_hash.c -msecure-plt -quiet -dumpbase dictionary_hash.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.621  as               467459 467451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o /tmp/ccHNIzEC.s\n13.648  as               467460 467457   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o /tmp/ccjKOVx6.s\n13.660  powerpc64le-lin  467461 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o -c brotli/enc/encode.c\n13.662  cc1              467462 467461   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/encode.c -msecure-plt -quiet -dumpbase encode.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.688  riscv64-linux-g  467463 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o -c brotli/enc/compress_fragment_two_pass.c\n13.690  cc1              467464 467463   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/compress_fragment_two_pass.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-compress_fragment_two_pass.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.866  as               467465 467461   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o /tmp/ccD4wouo.s\n13.889  as               467466 467463   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o /tmp/cc7wI7An.s\n13.890  powerpc64le-lin  467467 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o -c brotli/enc/entropy_encode.c\n13.892  cc1              467468 467467   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/entropy_encode.c -msecure-plt -quiet -dumpbase entropy_encode.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.920  as               467469 467467   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o /tmp/ccUwGNES.s\n13.929  powerpc64le-lin  467470 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o -c brotli/enc/histogram.c\n13.931  cc1              467471 467470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/histogram.c -msecure-plt -quiet -dumpbase histogram.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.944  riscv64-linux-g  467472 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o -c brotli/enc/dictionary_hash.c\n13.945  cc1              467473 467472   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/dictionary_hash.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-dictionary_hash.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.956  as               467474 467470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o /tmp/ccdplC63.s\n13.964  powerpc64le-lin  467475 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o -c brotli/enc/literal_cost.c\n13.965  cc1              467476 467475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/literal_cost.c -msecure-plt -quiet -dumpbase literal_cost.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.981  as               467477 467472   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o /tmp/cc6vLa2U.s\n13.990  as               467479 467475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o /tmp/ccPiYVat.s\n13.991  riscv64-linux-g  467478 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o -c brotli/enc/encode.c\n13.992  cc1              467480 467478   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/encode.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-encode.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.998  powerpc64le-lin  467481 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o -c brotli/enc/memory.c\n14.000  cc1              467482 467481   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/memory.c -msecure-plt -quiet -dumpbase memory.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n14.018  as               467483 467481   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o /tmp/ccccrRdU.s\n14.025  powerpc64le-lin  467484 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o -c brotli/enc/metablock.c\n14.027  cc1              467485 467484   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/metablock.c -msecure-plt -quiet -dumpbase metablock.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n14.103  as               467486 467484   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o /tmp/ccFnMr38.s\n14.116  powerpc64le-lin  467487 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o -c brotli/enc/static_dict.c\n14.118  cc1              467488 467487   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/static_dict.c -msecure-plt -quiet -dumpbase static_dict.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n14.221  as               467489 467478   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o /tmp/ccqDvI7W.s\n14.270  riscv64-linux-g  467490 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o -c brotli/enc/entropy_encode.c\n14.272  cc1              467491 467490   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/entropy_encode.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-entropy_encode.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.297  as               467492 467487   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o /tmp/cc2XVbsl.s\n14.298  as               467493 467490   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o /tmp/ccHomo7A.s\n14.306  riscv64-linux-g  467494 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o -c brotli/enc/histogram.c\n14.307  cc1              467495 467494   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/histogram.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-histogram.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.329  powerpc64le-lin  467496 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o -c brotli/enc/utf8_util.c\n14.330  cc1              467497 467496   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/utf8_util.c -msecure-plt -quiet -dumpbase utf8_util.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n14.332  as               467498 467494   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o /tmp/ccZvcoqW.s\n14.338  riscv64-linux-g  467499 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o -c brotli/enc/literal_cost.c\n14.340  cc1              467500 467499   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/literal_cost.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-literal_cost.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.346  as               467501 467496   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o /tmp/cc5uSpe5.s\n14.354  powerpc64le-lin  467502 467309   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o ...\n14.362  powerpc64le-lin  467503 467309   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a\n14.367  as               467504 467499   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o /tmp/ccH4vY28.s\n14.373  riscv64-linux-g  467507 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o -c brotli/enc/memory.c\n14.374  rustc            467506 466544   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name brotli_sys --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c79f4d53b620c131 ...\n14.375  cc1              467508 467507   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/memory.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-memory.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.390  as               467512 467507   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o /tmp/cc1l9i2A.s\n14.395  riscv64-linux-g  467513 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o -c brotli/enc/metablock.c\n14.397  cc1              467514 467513   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/metablock.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-metablock.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.476  as               467518 467513   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o /tmp/ccRXWm55.s\n14.496  riscv64-linux-g  467519 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o -c brotli/enc/static_dict.c\n14.498  cc1              467520 467519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/static_dict.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-static_dict.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.690  as               467521 467519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o /tmp/ccSLUSwl.s\n14.727  riscv64-linux-g  467522 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o -c brotli/enc/utf8_util.c\n14.728  cc1              467523 467522   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/utf8_util.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-utf8_util.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.740  as               467524 467522   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o /tmp/ccuTSl42.s\n14.746  riscv64-linux-g  467525 467213   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o ...\n14.783  riscv64-linux-g  467526 467213   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a\n14.826  rustc            467528 466421   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name brotli_sys --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28a7a4aa9eb732c2 ...\n15.471  cross            467535 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.472  rustc            467538 467535   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.477  rustc            467538 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.484  cross            467548 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n15.486  rustc            467553 467548   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.489  rustc            467562 467535   0 /home/xmoe/.cargo/bin/rustc -vV\n15.491  rustc            467553 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.494  rustc            467562 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.502  cargo            467575 467535   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.503  rustc            467576 467548   0 /home/xmoe/.cargo/bin/rustc -vV\n15.507  cargo            467575 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.509  rustc            467576 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.518  rustc            467595 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.518  cargo            467594 467548   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.523  cargo            467594 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.527  rustc            467605 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.533  rustc            467606 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.540  rustc            467610 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.542  rustc            467612 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.552  rustc            467619 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.554  rustc            467620 467535   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.559  rustc            467620 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.567  rustc            467635 467548   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.570  docker           467644 467535   0 /usr/bin/docker --help\n15.572  rustc            467635 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.583  docker           467660 467535   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.584  docker           467661 467548   0 /usr/bin/docker --help\n15.594  docker           467682 467548   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.595  runc             467683 1599     0 /usr/bin/runc --version\n15.598  docker-init      467694 1599     0 /usr/bin/docker-init --version\n15.599  docker           467695 467535   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.607  runc             467711 1599     0 /usr/bin/runc --version\n15.610  docker-init      467717 1599     0 /usr/bin/docker-init --version\n15.612  docker           467719 467548   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.612  runc             467722 1599     0 /usr/bin/runc --version\n15.615  docker-init      467733 1599     0 /usr/bin/docker-init --version\n15.623  runc             467739 1599     0 /usr/bin/runc --version\n15.627  docker-init      467745 1599     0 /usr/bin/docker-init --version\n15.636  rustup           467748 467535   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.642  rustup           467757 467535   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.650  rustup           467766 467548   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.656  rustup           467775 467548   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.665  rustup           467784 467535   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.680  rustup           467793 467548   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.689  uname            467802 467535   0 /usr/bin/uname -r\n15.703  uname            467803 467548   0 /usr/bin/uname -r\n15.707  docker           467804 467535   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.720  docker           467814 467548   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.755  systemd-sysctl   467830 467828   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha60e121 --prefix=/net/ipv4/neigh/vetha60e121 --prefix=/net/ipv6/conf/vetha60e121 --prefix=/net/ipv6/neigh/vetha60e121\n15.757  systemd-sysctl   467831 467829   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5d6981e --prefix=/net/ipv4/neigh/veth5d6981e --prefix=/net/ipv6/conf/veth5d6981e --prefix=/net/ipv6/neigh/veth5d6981e\n15.773  containerd-shim  467867 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee start\n15.774  systemd-sysctl   467866 467842   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth00063ae --prefix=/net/ipv4/neigh/veth00063ae --prefix=/net/ipv6/conf/veth00063ae --prefix=/net/ipv6/neigh/veth00063ae\n15.776  systemd-sysctl   467871 467853   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth40e6fa1 --prefix=/net/ipv4/neigh/veth40e6fa1 --prefix=/net/ipv6/conf/veth40e6fa1 --prefix=/net/ipv6/neigh/veth40e6fa1\n15.778  containerd-shim  467875 467867   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee -address /var/run/docker/containerd/containerd.sock\n15.781  runc             467884 467875   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee\n15.786  containerd-shim  467890 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 start\n15.790  exe              467899 467884   0 \n15.791  containerd-shim  467900 467890   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 -address /var/run/docker/containerd/containerd.sock\n15.794  runc             467912 467900   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490\n15.800  exe              467920 467912   0 /proc/self/exe init\n15.825  exe              467936 467884   0 /proc/1599/exe -exec-root=/var/run/docker a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee d7da31e8f8e1\n15.826  exe              467937 467912   0 /proc/1599/exe -exec-root=/var/run/docker 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 d7da31e8f8e1\n15.845  exe              467952 1599     0 /proc/self/exe /var/run/docker/netns/67593d8830ed all false\n15.846  exe              467953 1599     0 /proc/self/exe /var/run/docker/netns/3c05773b9ce6 all false\n16.045  runc             467990 467900   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --log-format json --systemd-cgroup start 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490\n16.046  runc             467991 467875   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --log-format json --systemd-cgroup start a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee\n16.051  sh               467930 467900   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.052  sh               467923 467875   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.052  cargo            468002 467930   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.054  cargo            468003 467923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.063  cargo-native-tr  468003 467923   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.063  cargo-native-tr  468002 467930   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.067  cargo            468004 468003   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.067  cargo            468005 468002   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.078  rustc            468006 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.078  rustc            468007 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.089  rustc            468010 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.090  rustc            468011 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.104  execsnoop        468018 468002   0 /usr/local/bin/execsnoop -t\n16.104  python3          468018 468002   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.104  execsnoop        468021 468003   0 /usr/local/bin/execsnoop -t\n16.105  python3          468021 468003   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.599  runc             468024 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2801572281 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n16.605  exe              468031 468024   0 /proc/self/exe init\n16.622  curl             468034 468024   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n16.855  sh               468040 2147557   0 /bin/sh -c which ps\n16.857  which            468040 2147557   0 /usr/bin/which ps\n16.859  sh               468041 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.860  ps               468041 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.887  sh               468042 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.889  cpuUsage.sh      468042 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.890  sed              468043 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.892  cat              468044 468042   0 /usr/bin/cat /proc/2240539/stat\n16.894  cat              468045 468042   0 /usr/bin/cat /proc/4193716/stat\n16.895  sleep            468046 468042   0 /usr/bin/sleep 1\n17.897  sed              468047 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.899  cat              468048 468042   0 /usr/bin/cat /proc/2240539/stat\n17.901  cat              468050 468042   0 /usr/bin/cat /proc/4193716/stat\n17.969  cargo            468052 468002   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.982  rustc            468053 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.000  rustc            468059 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n18.043  cc               468079 468059   0 /tmp/native-trace-468002-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.045  cc               468080 468079   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.048  collect2         468081 468080   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.049  ld.lld           468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n18.050  rust-lld         468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.086  build-script-bu  468100 468052   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n18.092  rustc            468102 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=01dbfa75f86e934e ...\n18.240  cargo            468109 468003   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.253  rustc            468110 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.272  rustc            468116 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n18.294  runc             468120 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup kill --all c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 9\n18.312  runc             468143 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup delete c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n18.313  cc               468142 468116   0 /tmp/native-trace-468003-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.315  cc               468149 468142   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n18.317  collect2         468150 468149   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.319  ld.lld           468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n18.321  rust-lld         468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.365  build-script-bu  468169 468109   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n18.371  rustc            468171 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=eb508d71aca425cd ...\n18.507  containerd-shim  468178 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d delete\n18.509  runc             468184 468178   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b7 --log-format json delete --force c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n"
    },
    {
      "argv": [
        "/target/debug/build/substring-049b5fca247331ec/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 462826,
      "build_script_target_dir": "substring-049b5fca247331ec",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/substring-049b5fca247331ec/build-script-build",
      "pid": 462826,
      "ppid": 462470,
      "root_cargo_pid": 462470,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 462826,
      "build_script_target_dir": "substring-049b5fca247331ec",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 462829,
      "ppid": 462826,
      "root_cargo_pid": 462470,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_abccccb438587ecf_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/substring-b7ed59fe071f9b2b/out",
        "--emit=llvm-ir",
        "--target",
        "aarch64-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 462826,
      "build_script_target_dir": "substring-049b5fca247331ec",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 462843,
      "ppid": 462826,
      "root_cargo_pid": 462470,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "substring",
      "cwd": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "event_id": "bsrun:222356d3a3b01f01:bebeb726cf26c996:0b6d9a1c468b957a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/substring-049b5fca247331ec/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
      "out_dir": "/target/debug/build/substring-049b5fca247331ec/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
      "success": true,
      "target": null,
      "version": "1.4.5",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-aarch64-ev1ejfue/src/substring-1.4.5",
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
      "build_script_root_pid": 462826,
      "build_script_target_dir": "substring-049b5fca247331ec",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 462829,
      "ppid": 462826,
      "root_cargo_pid": 462470,
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
        "autocfg_abccccb438587ecf_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/substring-b7ed59fe071f9b2b/out",
        "--emit=llvm-ir",
        "--target",
        "aarch64-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 462826,
      "build_script_target_dir": "substring-049b5fca247331ec",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 462843,
      "ppid": 462826,
      "root_cargo_pid": 462470,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 1990,
    "crate": "substring",
    "version": "1.4.5",
    "crate_id": "298416",
    "version_id": "335417",
    "downloads": 7262985,
    "cumulative_downloads": 101662927620,
    "cumulative_share_of_global": 0.38009421689315165,
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
