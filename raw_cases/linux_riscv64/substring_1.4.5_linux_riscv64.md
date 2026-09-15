# `substring` `1.4.5`

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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J",
    "/target/debug/build/substring-049b5fca247331ec",
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
      "directory": "/target/debug/build/substring-049b5fca247331ec/rustcXO473J",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-463311-1783994523269069032.map",
  "pid": 463311,
  "ppid": 463282,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-463311-1783994523269069032.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "workspace_root": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5"
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
      "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
      "name": "substring",
      "version": "1.4.5",
      "manifest_path": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5"
    }
  ],
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 463311,
  "ppid": 463282,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "event_id": "used:cc:fec48f84af16f1eb:ec21151bead44d6b:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
  "pid": 463311,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "event_id": "used:cc:fec48f84af16f1eb:3be92e85c7a31afd:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
  "pid": 463311,
  "sha256": "60ab71f575cd6462019f2fcbb5d17d2bf98e5f912849b359d686e84844c357a9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "event_id": "used:cc:fec48f84af16f1eb:dc50a37b355a5204:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
  "pid": 463311,
  "sha256": "21935d4a46162b9648e16312cb117e316b63b41e8e0f8e5c3873cdf95c0ed5a6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "event_id": "used:cc:fec48f84af16f1eb:f33b3bed1fbde522:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
  "pid": 463311,
  "sha256": "6ea6c6770da768af644446dba36adc7d51181089f1e0adafc1aaf50c1ef048e0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "event_id": "used:cc:fec48f84af16f1eb:ae0eff6e1280ab94:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
  "pid": 463311,
  "sha256": "5b2cb3e0099fa97ac680f8fa23ad2742772190f284339261c5e3d3cc2037f7e7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "event_id": "used:cc:fec48f84af16f1eb:49ddcc950e1bef76:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
  "pid": 463311,
  "sha256": "9c07d168adf426042af910b36bdb11e56277b0674053dfca9c104e189f7b79f3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "event_id": "used:cc:fec48f84af16f1eb:9be13078a345341b:4ef946e29201bf7f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
  "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
  "pid": 463311,
  "sha256": "fef839a40b37fde68d6749a1767745534a9dcce814d20139fce2047d9590b58a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "cargo_pkg_name": "substring",
  "cargo_pkg_version": "1.4.5",
  "context_path": "/tmp/native-trace-461445-1783994517551/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-461445-1783994517551/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 463311,
  "ppid": 463282,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
    "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/substring-049b5fca247331ec/rustcXO473J",
    "/target/debug/build/substring-049b5fca247331ec",
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
      "directory": "/target/debug/build/substring-049b5fca247331ec/rustcXO473J",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/substring-049b5fca247331ec",
      "kind": "object",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-463311-1783994523269069032.map",
  "pid": 463311,
  "ppid": 463282,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-463311-1783994523269069032.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
  "parsed_event_count": 1202,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1203,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "ess_fragment.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n12.606  as               467447 467436   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o /tmp/ccLsJJqy.s\n12.635  riscv64-linux-g  467448 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o -c brotli/enc/cluster.c\n12.637  cc1              467449 467448   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/cluster.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-cluster.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n12.701  as               467450 467448   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o /tmp/cc6fZGYO.s\n12.716  riscv64-linux-g  467451 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o -c brotli/enc/compress_fragment.c\n12.718  cc1              467452 467451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/compress_fragment.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-compress_fragment.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n12.756  as               467453 467445   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o /tmp/ccQBGv8d.s\n12.781  powerpc64le-lin  467454 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o -c brotli/enc/compress_fragment_two_pass.c\n12.783  cc1              467455 467454   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/compress_fragment_two_pass.c -msecure-plt -quiet -dumpbase compress_fragment_two_pass.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n12.972  as               467456 467454   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o /tmp/ccWkXESU.s\n12.999  powerpc64le-lin  467457 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o -c brotli/enc/dictionary_hash.c\n13.001  cc1              467458 467457   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/dictionary_hash.c -msecure-plt -quiet -dumpbase dictionary_hash.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.008  as               467459 467451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o /tmp/ccHNIzEC.s\n13.036  as               467460 467457   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o /tmp/ccjKOVx6.s\n13.048  powerpc64le-lin  467461 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o -c brotli/enc/encode.c\n13.049  cc1              467462 467461   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/encode.c -msecure-plt -quiet -dumpbase encode.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.076  riscv64-linux-g  467463 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o -c brotli/enc/compress_fragment_two_pass.c\n13.077  cc1              467464 467463   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/compress_fragment_two_pass.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-compress_fragment_two_pass.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.253  as               467465 467461   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o /tmp/ccD4wouo.s\n13.276  as               467466 467463   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o /tmp/cc7wI7An.s\n13.278  powerpc64le-lin  467467 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o -c brotli/enc/entropy_encode.c\n13.279  cc1              467468 467467   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/entropy_encode.c -msecure-plt -quiet -dumpbase entropy_encode.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.307  as               467469 467467   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o /tmp/ccUwGNES.s\n13.316  powerpc64le-lin  467470 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o -c brotli/enc/histogram.c\n13.318  cc1              467471 467470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/histogram.c -msecure-plt -quiet -dumpbase histogram.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.331  riscv64-linux-g  467472 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o -c brotli/enc/dictionary_hash.c\n13.333  cc1              467473 467472   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/dictionary_hash.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-dictionary_hash.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.343  as               467474 467470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o /tmp/ccdplC63.s\n13.351  powerpc64le-lin  467475 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o -c brotli/enc/literal_cost.c\n13.353  cc1              467476 467475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/literal_cost.c -msecure-plt -quiet -dumpbase literal_cost.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.368  as               467477 467472   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o /tmp/cc6vLa2U.s\n13.378  as               467479 467475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o /tmp/ccPiYVat.s\n13.378  riscv64-linux-g  467478 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o -c brotli/enc/encode.c\n13.380  cc1              467480 467478   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/encode.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-encode.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.386  powerpc64le-lin  467481 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o -c brotli/enc/memory.c\n13.387  cc1              467482 467481   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/memory.c -msecure-plt -quiet -dumpbase memory.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.406  as               467483 467481   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o /tmp/ccccrRdU.s\n13.412  powerpc64le-lin  467484 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o -c brotli/enc/metablock.c\n13.414  cc1              467485 467484   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/metablock.c -msecure-plt -quiet -dumpbase metablock.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.490  as               467486 467484   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o /tmp/ccFnMr38.s\n13.503  powerpc64le-lin  467487 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o -c brotli/enc/static_dict.c\n13.505  cc1              467488 467487   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/static_dict.c -msecure-plt -quiet -dumpbase static_dict.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.608  as               467489 467478   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o /tmp/ccqDvI7W.s\n13.657  riscv64-linux-g  467490 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o -c brotli/enc/entropy_encode.c\n13.659  cc1              467491 467490   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/entropy_encode.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-entropy_encode.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.684  as               467492 467487   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o /tmp/cc2XVbsl.s\n13.685  as               467493 467490   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o /tmp/ccHomo7A.s\n13.693  riscv64-linux-g  467494 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o -c brotli/enc/histogram.c\n13.695  cc1              467495 467494   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/histogram.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-histogram.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.716  powerpc64le-lin  467496 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o -c brotli/enc/utf8_util.c\n13.718  cc1              467497 467496   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/utf8_util.c -msecure-plt -quiet -dumpbase utf8_util.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.719  as               467498 467494   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o /tmp/ccZvcoqW.s\n13.725  riscv64-linux-g  467499 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o -c brotli/enc/literal_cost.c\n13.727  cc1              467500 467499   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/literal_cost.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-literal_cost.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.733  as               467501 467496   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o /tmp/cc5uSpe5.s\n13.741  powerpc64le-lin  467502 467309   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o ...\n13.749  powerpc64le-lin  467503 467309   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a\n13.754  as               467504 467499   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o /tmp/ccH4vY28.s\n13.760  riscv64-linux-g  467507 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o -c brotli/enc/memory.c\n13.761  rustc            467506 466544   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name brotli_sys --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c79f4d53b620c131 ...\n13.762  cc1              467508 467507   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/memory.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-memory.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.777  as               467512 467507   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o /tmp/cc1l9i2A.s\n13.782  riscv64-linux-g  467513 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o -c brotli/enc/metablock.c\n13.784  cc1              467514 467513   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/metablock.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-metablock.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.864  as               467518 467513   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o /tmp/ccRXWm55.s\n13.883  riscv64-linux-g  467519 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o -c brotli/enc/static_dict.c\n13.885  cc1              467520 467519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/static_dict.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-static_dict.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.077  as               467521 467519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o /tmp/ccSLUSwl.s\n14.114  riscv64-linux-g  467522 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o -c brotli/enc/utf8_util.c\n14.116  cc1              467523 467522   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/utf8_util.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-utf8_util.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.128  as               467524 467522   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o /tmp/ccuTSl42.s\n14.133  riscv64-linux-g  467525 467213   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o ...\n14.170  riscv64-linux-g  467526 467213   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a\n14.213  rustc            467528 466421   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name brotli_sys --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28a7a4aa9eb732c2 ...\n14.858  cross            467535 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n14.859  rustc            467538 467535   0 /home/xmoe/.cargo/bin/rustc --print target-list\n14.864  rustc            467538 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n14.871  cross            467548 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n14.873  rustc            467553 467548   0 /home/xmoe/.cargo/bin/rustc --print target-list\n14.876  rustc            467562 467535   0 /home/xmoe/.cargo/bin/rustc -vV\n14.878  rustc            467553 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n14.881  rustc            467562 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.890  cargo            467575 467535   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n14.890  rustc            467576 467548   0 /home/xmoe/.cargo/bin/rustc -vV\n14.895  cargo            467575 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n14.896  rustc            467576 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.905  rustc            467595 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.905  cargo            467594 467548   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n14.910  cargo            467594 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n14.914  rustc            467605 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.920  rustc            467606 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.927  rustc            467610 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.929  rustc            467612 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.940  rustc            467619 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.941  rustc            467620 467535   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n14.946  rustc            467620 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n14.954  rustc            467635 467548   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n14.957  docker           467644 467535   0 /usr/bin/docker --help\n14.960  rustc            467635 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n14.970  docker           467660 467535   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n14.971  docker           467661 467548   0 /usr/bin/docker --help\n14.982  docker           467682 467548   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n14.983  runc             467683 1599     0 /usr/bin/runc --version\n14.985  docker-init      467694 1599     0 /usr/bin/docker-init --version\n14.987  docker           467695 467535   0 /usr/bin/docker info -f {{.SecurityOptions}}\n14.994  runc             467711 1599     0 /usr/bin/runc --version\n14.997  docker-init      467717 1599     0 /usr/bin/docker-init --version\n14.999  docker           467719 467548   0 /usr/bin/docker info -f {{.SecurityOptions}}\n14.999  runc             467722 1599     0 /usr/bin/runc --version\n15.002  docker-init      467733 1599     0 /usr/bin/docker-init --version\n15.011  runc             467739 1599     0 /usr/bin/runc --version\n15.014  docker-init      467745 1599     0 /usr/bin/docker-init --version\n15.023  rustup           467748 467535   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.029  rustup           467757 467535   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.037  rustup           467766 467548   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.043  rustup           467775 467548   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.053  rustup           467784 467535   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.067  rustup           467793 467548   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.077  uname            467802 467535   0 /usr/bin/uname -r\n15.090  uname            467803 467548   0 /usr/bin/uname -r\n15.094  docker           467804 467535   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.107  docker           467814 467548   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.142  systemd-sysctl   467830 467828   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha60e121 --prefix=/net/ipv4/neigh/vetha60e121 --prefix=/net/ipv6/conf/vetha60e121 --prefix=/net/ipv6/neigh/vetha60e121\n15.144  systemd-sysctl   467831 467829   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5d6981e --prefix=/net/ipv4/neigh/veth5d6981e --prefix=/net/ipv6/conf/veth5d6981e --prefix=/net/ipv6/neigh/veth5d6981e\n15.161  containerd-shim  467867 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee start\n15.161  systemd-sysctl   467866 467842   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth00063ae --prefix=/net/ipv4/neigh/veth00063ae --prefix=/net/ipv6/conf/veth00063ae --prefix=/net/ipv6/neigh/veth00063ae\n15.163  systemd-sysctl   467871 467853   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth40e6fa1 --prefix=/net/ipv4/neigh/veth40e6fa1 --prefix=/net/ipv6/conf/veth40e6fa1 --prefix=/net/ipv6/neigh/veth40e6fa1\n15.165  containerd-shim  467875 467867   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee -address /var/run/docker/containerd/containerd.sock\n15.168  runc             467884 467875   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee\n15.173  containerd-shim  467890 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 start\n15.177  exe              467899 467884   0 /proc/self/exe init\n15.179  containerd-shim  467900 467890   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 -address /var/run/docker/containerd/containerd.sock\n15.182  runc             467912 467900   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490\n15.187  exe              467920 467912   0 /proc/self/exe init\n15.212  exe              467936 467884   0 /proc/1599/exe -exec-root=/var/run/docker a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee d7da31e8f8e1\n15.213  exe              467937 467912   0 /proc/1599/exe -exec-root=/var/run/docker 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 d7da31e8f8e1\n15.233  exe              467952 1599     0 /proc/self/exe /var/run/docker/netns/67593d8830ed all false\n15.233  exe              467953 1599     0 /proc/self/exe /var/run/docker/netns/3c05773b9ce6 all false\n15.432  runc             467990 467900   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --log-format json --systemd-cgroup start 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490\n15.433  runc             467991 467875   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --log-format json --systemd-cgroup start a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee\n15.438  sh               467930 467900   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.439  sh               467923 467875   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.439  cargo            468002 467930   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n15.440  cargo            468003 467923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.450  cargo-native-tr  468003 467923   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.451  cargo-native-tr  468002 467930   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n15.454  cargo            468004 468003   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.454  cargo            468005 468002   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.465  rustc            468006 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.465  rustc            468007 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.477  rustc            468010 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.477  rustc            468011 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.491  execsnoop        468018 468002   0 /usr/local/bin/execsnoop -t\n15.491  python3          468018 468002   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.492  execsnoop        468021 468003   0 /usr/local/bin/execsnoop -t\n15.492  python3          468021 468003   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.986  runc             468024 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2801572281 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n15.992  exe              468031 468024   0 /proc/self/exe init\n16.009  curl             468034 468024   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n16.243  sh               468040 2147557   0 /bin/sh -c which ps\n16.244  which            468040 2147557   0 /usr/bin/which ps\n16.246  sh               468041 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.248  ps               468041 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.274  sh               468042 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.276  cpuUsage.sh      468042 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.277  sed              468043 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.279  cat              468044 468042   0 /usr/bin/cat /proc/2240539/stat\n16.281  cat              468045 468042   0 /usr/bin/cat /proc/4193716/stat\n16.282  sleep            468046 468042   0 /usr/bin/sleep 1\n17.284  sed              468047 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.286  cat              468048 468042   0 /usr/bin/cat /proc/2240539/stat\n17.288  cat              468050 468042   0 /usr/bin/cat /proc/4193716/stat\n17.356  cargo            468052 468002   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.369  rustc            468053 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.388  rustc            468059 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n17.431  cc               468079 468059   0 /tmp/native-trace-468002-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n17.432  cc               468080 468079   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n17.435  collect2         468081 468080   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.436  ld.lld           468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n17.438  rust-lld         468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.474  build-script-bu  468100 468052   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n17.479  rustc            468102 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=01dbfa75f86e934e ...\n17.627  cargo            468109 468003   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n17.640  rustc            468110 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.659  rustc            468116 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n17.681  runc             468120 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup kill --all c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 9\n17.699  runc             468143 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup delete c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n17.701  cc               468142 468116   0 /tmp/native-trace-468003-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n17.702  cc               468149 468142   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n17.705  collect2         468150 468149   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.706  ld.lld           468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n17.708  rust-lld         468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.752  build-script-bu  468169 468109   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n17.758  rustc            468171 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=eb508d71aca425cd ...\n17.894  containerd-shim  468178 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d delete\n17.896  runc             468184 468178   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b7 --log-format json delete --force c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n17.957  systemd-sysctl   468190 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth26ae1bd --prefix=/net/ipv4/neigh/veth26ae1bd --prefix=/net/ipv6/conf/veth26ae1bd --prefix=/net/ipv6/neigh/veth26ae1bd\n17.968  runc             468191 461041   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb --log-format json --systemd-cgroup kill --all 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468 9\n17.985  runc             468197 461041   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb --log-format json --systemd-cgroup delete 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468\n18.190  containerd-shim  468203 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb delete\n18.192  runc             468209 468203   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed46 --log-format json delete --force 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468\n18.232  sh               468217 467838   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth83795da\n18.233  ethtool          468218 468217   0 /usr/sbin/ethtool -i veth83795da\n18.234  sed              468219 468217   0 /usr/bin/sed -n s/^driver: //p\n18.239  systemd-sysctl   468222 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth83795da --prefix=/net/ipv4/neigh/veth83795da --prefix=/net/ipv6/conf/veth83795da --prefix=/net/ipv6/neigh/veth83795da\n18.386  runc             468224 461102   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c --log-format json --systemd-cgroup kill --all aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358 9\n18.404  runc             468230 461102   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c --log-format json --systemd-cgroup delete aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358\n18.484  runc             468236 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process812323305 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n18.489  exe              468243 468236   0 /proc/self/exe init\n18.498  curl             468245 468236   0 /usr/bin/curl -f http://localhost:9091/healthz\n18.580  containerd-shim  468252 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c delete\n18.582  runc             468259 468252   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a35 --log-format json delete --force aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358\n18.626  systemd-sysctl   468264 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth61a52e7 --prefix=/net/ipv4/neigh/veth61a52e7 --prefix=/net/ipv6/conf/veth61a52e7 --prefix=/net/ipv6/neigh/veth61a52e7\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/substring-049b5fca247331ec/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463392,
  "build_script_target_dir": "substring-049b5fca247331ec",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/substring-049b5fca247331ec/build-script-build",
  "pid": 463392,
  "ppid": 462636,
  "root_cargo_pid": 462636,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
  "build_script_root_pid": 463392,
  "build_script_target_dir": "substring-049b5fca247331ec",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 463394,
  "ppid": 463392,
  "root_cargo_pid": 462636,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "_build_script_out_dir": "/target/debug/build/substring-049b5fca247331ec/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 17

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_e188066370c82351_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/substring-85ebc2609a4e6a65/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463392,
  "build_script_target_dir": "substring-049b5fca247331ec",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 463402,
  "ppid": 463392,
  "root_cargo_pid": 462636,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "_build_script_out_dir": "/target/debug/build/substring-049b5fca247331ec/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 18

```json
{
  "crate": "substring",
  "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "event_id": "bsrun:0b51861e31765141:bebeb726cf26c996:0b6d9a1c468b957a",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/substring-049b5fca247331ec/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
  "out_dir": "/target/debug/build/substring-049b5fca247331ec/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
  "success": true,
  "target": null,
  "version": "1.4.5",
  "_owner": {
    "crate": "substring",
    "version": "1.4.5",
    "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
    "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
  "build_script_root_pid": 463392,
  "build_script_target_dir": "substring-049b5fca247331ec",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 463394,
  "ppid": 463392,
  "root_cargo_pid": 462636,
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
    "autocfg_e188066370c82351_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/substring-85ebc2609a4e6a65/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 463392,
  "build_script_target_dir": "substring-049b5fca247331ec",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 463402,
  "ppid": 463392,
  "root_cargo_pid": 462636,
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
  "time": "2026-07-14T02:02:21.297944+00:00",
  "crate": "substring",
  "version": "1.4.5",
  "architecture": "riscv64",
  "duration_seconds": 29.654966755304486,
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
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "manifest_path": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "workspace_root": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5"
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
          "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
          "name": "substring",
          "version": "1.4.5",
          "manifest_path": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5"
        }
      ],
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 463311,
      "ppid": 463282,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "event_id": "used:cc:fec48f84af16f1eb:ec21151bead44d6b:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
      "pid": 463311,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "event_id": "used:cc:fec48f84af16f1eb:3be92e85c7a31afd:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
      "pid": 463311,
      "sha256": "60ab71f575cd6462019f2fcbb5d17d2bf98e5f912849b359d686e84844c357a9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "event_id": "used:cc:fec48f84af16f1eb:dc50a37b355a5204:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
      "pid": 463311,
      "sha256": "21935d4a46162b9648e16312cb117e316b63b41e8e0f8e5c3873cdf95c0ed5a6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "event_id": "used:cc:fec48f84af16f1eb:f33b3bed1fbde522:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
      "pid": 463311,
      "sha256": "6ea6c6770da768af644446dba36adc7d51181089f1e0adafc1aaf50c1ef048e0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "event_id": "used:cc:fec48f84af16f1eb:ae0eff6e1280ab94:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
      "pid": 463311,
      "sha256": "5b2cb3e0099fa97ac680f8fa23ad2742772190f284339261c5e3d3cc2037f7e7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "event_id": "used:cc:fec48f84af16f1eb:49ddcc950e1bef76:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
      "pid": 463311,
      "sha256": "9c07d168adf426042af910b36bdb11e56277b0674053dfca9c104e189f7b79f3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "event_id": "used:cc:fec48f84af16f1eb:9be13078a345341b:4ef946e29201bf7f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec",
      "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
      "pid": 463311,
      "sha256": "fef839a40b37fde68d6749a1767745534a9dcce814d20139fce2047d9590b58a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "cargo_pkg_name": "substring",
      "cargo_pkg_version": "1.4.5",
      "context_path": "/tmp/native-trace-461445-1783994517551/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-461445-1783994517551/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 463311,
      "ppid": 463282,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
        "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/substring-049b5fca247331ec/rustcXO473J",
        "/target/debug/build/substring-049b5fca247331ec",
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
          "directory": "/target/debug/build/substring-049b5fca247331ec/rustcXO473J",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/rustcXO473J/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.3q5nfz05ftvnb5ixtern0f7yw.1mrvr3i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4naydh8vftm2s9mv9jq35npv6.1mrvr3i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.9e81e1jaq6i9ve0xjxsghdbdm.1mrvr3i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bjv5jmf6xgjmajv4wfopqappu.1mrvr3i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.bxbhobylb6qpjzq9n3o01ryzk.1mrvr3i.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/substring-049b5fca247331ec",
          "kind": "object",
          "path": "/target/debug/build/substring-049b5fca247331ec/build_script_build-049b5fca247331ec.4cuykmb6hemvuou0zz00xeirc.1mrvr3i.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-463311-1783994523269069032.map",
      "pid": 463311,
      "ppid": 463282,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-463311-1783994523269069032.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
      "parsed_event_count": 1202,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1203,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "ess_fragment.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n12.606  as               467447 467436   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o /tmp/ccLsJJqy.s\n12.635  riscv64-linux-g  467448 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o -c brotli/enc/cluster.c\n12.637  cc1              467449 467448   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/cluster.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-cluster.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n12.701  as               467450 467448   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o /tmp/cc6fZGYO.s\n12.716  riscv64-linux-g  467451 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o -c brotli/enc/compress_fragment.c\n12.718  cc1              467452 467451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/compress_fragment.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-compress_fragment.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n12.756  as               467453 467445   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o /tmp/ccQBGv8d.s\n12.781  powerpc64le-lin  467454 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o -c brotli/enc/compress_fragment_two_pass.c\n12.783  cc1              467455 467454   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/compress_fragment_two_pass.c -msecure-plt -quiet -dumpbase compress_fragment_two_pass.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n12.972  as               467456 467454   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o /tmp/ccWkXESU.s\n12.999  powerpc64le-lin  467457 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o -c brotli/enc/dictionary_hash.c\n13.001  cc1              467458 467457   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/dictionary_hash.c -msecure-plt -quiet -dumpbase dictionary_hash.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.008  as               467459 467451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o /tmp/ccHNIzEC.s\n13.036  as               467460 467457   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o /tmp/ccjKOVx6.s\n13.048  powerpc64le-lin  467461 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o -c brotli/enc/encode.c\n13.049  cc1              467462 467461   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/encode.c -msecure-plt -quiet -dumpbase encode.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.076  riscv64-linux-g  467463 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o -c brotli/enc/compress_fragment_two_pass.c\n13.077  cc1              467464 467463   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/compress_fragment_two_pass.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-compress_fragment_two_pass.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.253  as               467465 467461   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o /tmp/ccD4wouo.s\n13.276  as               467466 467463   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o /tmp/cc7wI7An.s\n13.278  powerpc64le-lin  467467 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o -c brotli/enc/entropy_encode.c\n13.279  cc1              467468 467467   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/entropy_encode.c -msecure-plt -quiet -dumpbase entropy_encode.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.307  as               467469 467467   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o /tmp/ccUwGNES.s\n13.316  powerpc64le-lin  467470 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o -c brotli/enc/histogram.c\n13.318  cc1              467471 467470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/histogram.c -msecure-plt -quiet -dumpbase histogram.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.331  riscv64-linux-g  467472 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o -c brotli/enc/dictionary_hash.c\n13.333  cc1              467473 467472   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/dictionary_hash.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-dictionary_hash.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.343  as               467474 467470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o /tmp/ccdplC63.s\n13.351  powerpc64le-lin  467475 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o -c brotli/enc/literal_cost.c\n13.353  cc1              467476 467475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/literal_cost.c -msecure-plt -quiet -dumpbase literal_cost.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.368  as               467477 467472   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o /tmp/cc6vLa2U.s\n13.378  as               467479 467475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-literal_cost.o /tmp/ccPiYVat.s\n13.378  riscv64-linux-g  467478 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o -c brotli/enc/encode.c\n13.380  cc1              467480 467478   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/encode.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-encode.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.386  powerpc64le-lin  467481 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o -c brotli/enc/memory.c\n13.387  cc1              467482 467481   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/memory.c -msecure-plt -quiet -dumpbase memory.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.406  as               467483 467481   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-memory.o /tmp/ccccrRdU.s\n13.412  powerpc64le-lin  467484 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o -c brotli/enc/metablock.c\n13.414  cc1              467485 467484   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/metablock.c -msecure-plt -quiet -dumpbase metablock.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.490  as               467486 467484   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-metablock.o /tmp/ccFnMr38.s\n13.503  powerpc64le-lin  467487 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o -c brotli/enc/static_dict.c\n13.505  cc1              467488 467487   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/static_dict.c -msecure-plt -quiet -dumpbase static_dict.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.608  as               467489 467478   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o /tmp/ccqDvI7W.s\n13.657  riscv64-linux-g  467490 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o -c brotli/enc/entropy_encode.c\n13.659  cc1              467491 467490   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/entropy_encode.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-entropy_encode.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.684  as               467492 467487   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-static_dict.o /tmp/cc2XVbsl.s\n13.685  as               467493 467490   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o /tmp/ccHomo7A.s\n13.693  riscv64-linux-g  467494 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o -c brotli/enc/histogram.c\n13.695  cc1              467495 467494   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/histogram.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-histogram.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.716  powerpc64le-lin  467496 467309   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -I brotli/include -w -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o -c brotli/enc/utf8_util.c\n13.718  cc1              467497 467496   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I brotli/include -imultiarch powerpc64le-linux-gnu brotli/enc/utf8_util.c -msecure-plt -quiet -dumpbase utf8_util.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o -g -gdwarf-4 -O0 -w -ffunction-sections ...\n13.719  as               467498 467494   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o /tmp/ccZvcoqW.s\n13.725  riscv64-linux-g  467499 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o -c brotli/enc/literal_cost.c\n13.727  cc1              467500 467499   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/literal_cost.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-literal_cost.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.733  as               467501 467496   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I brotli/include -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-utf8_util.o /tmp/cc5uSpe5.s\n13.741  powerpc64le-lin  467502 467309   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/e198953d800c79d4-dictionary.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-bit_reader.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-decode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-huffman.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/76d4580618152496-state.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-backward_references_hq.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-bit_cost.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-block_splitter.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-brotli_bit_stream.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-cluster.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-compress_fragment_two_pass.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-dictionary_hash.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-encode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-entropy_encode.o /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/62394abbbe01bffa-histogram.o ...\n13.749  powerpc64le-lin  467503 467309   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/brotli-sys-be7822e4bad1c58d/out/libbrotli.a\n13.754  as               467504 467499   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-literal_cost.o /tmp/ccH4vY28.s\n13.760  riscv64-linux-g  467507 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o -c brotli/enc/memory.c\n13.761  rustc            467506 466544   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name brotli_sys --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c79f4d53b620c131 ...\n13.762  cc1              467508 467507   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/memory.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-memory.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.777  as               467512 467507   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-memory.o /tmp/cc1l9i2A.s\n13.782  riscv64-linux-g  467513 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o -c brotli/enc/metablock.c\n13.784  cc1              467514 467513   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/metablock.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-metablock.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n13.864  as               467518 467513   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-metablock.o /tmp/ccRXWm55.s\n13.883  riscv64-linux-g  467519 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o -c brotli/enc/static_dict.c\n13.885  cc1              467520 467519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/static_dict.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-static_dict.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.077  as               467521 467519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-static_dict.o /tmp/ccSLUSwl.s\n14.114  riscv64-linux-g  467522 467213   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I brotli/include -w -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o -c brotli/enc/utf8_util.c\n14.116  cc1              467523 467522   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I brotli/include -imultilib . -imultiarch riscv64-linux-gnu brotli/enc/utf8_util.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/ -dumpbase 62394abbbe01bffa-utf8_util.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.128  as               467524 467522   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I brotli/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-utf8_util.o /tmp/ccuTSl42.s\n14.133  riscv64-linux-g  467525 467213   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/e198953d800c79d4-dictionary.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-bit_reader.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-decode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-huffman.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/76d4580618152496-state.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-backward_references_hq.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-bit_cost.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-block_splitter.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-brotli_bit_stream.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-cluster.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-compress_fragment_two_pass.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-dictionary_hash.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-encode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-entropy_encode.o /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/62394abbbe01bffa-histogram.o ...\n14.170  riscv64-linux-g  467526 467213   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/brotli-sys-82fc7f4ca75fbd2e/out/libbrotli.a\n14.213  rustc            467528 466421   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name brotli_sys --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=28a7a4aa9eb732c2 ...\n14.858  cross            467535 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n14.859  rustc            467538 467535   0 /home/xmoe/.cargo/bin/rustc --print target-list\n14.864  rustc            467538 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n14.871  cross            467548 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n14.873  rustc            467553 467548   0 /home/xmoe/.cargo/bin/rustc --print target-list\n14.876  rustc            467562 467535   0 /home/xmoe/.cargo/bin/rustc -vV\n14.878  rustc            467553 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n14.881  rustc            467562 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.890  cargo            467575 467535   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n14.890  rustc            467576 467548   0 /home/xmoe/.cargo/bin/rustc -vV\n14.895  cargo            467575 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n14.896  rustc            467576 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.905  rustc            467595 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.905  cargo            467594 467548   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n14.910  cargo            467594 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n14.914  rustc            467605 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.920  rustc            467606 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.927  rustc            467610 467575   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.929  rustc            467612 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.940  rustc            467619 467594   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.941  rustc            467620 467535   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n14.946  rustc            467620 467535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n14.954  rustc            467635 467548   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n14.957  docker           467644 467535   0 /usr/bin/docker --help\n14.960  rustc            467635 467548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n14.970  docker           467660 467535   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n14.971  docker           467661 467548   0 /usr/bin/docker --help\n14.982  docker           467682 467548   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n14.983  runc             467683 1599     0 /usr/bin/runc --version\n14.985  docker-init      467694 1599     0 /usr/bin/docker-init --version\n14.987  docker           467695 467535   0 /usr/bin/docker info -f {{.SecurityOptions}}\n14.994  runc             467711 1599     0 /usr/bin/runc --version\n14.997  docker-init      467717 1599     0 /usr/bin/docker-init --version\n14.999  docker           467719 467548   0 /usr/bin/docker info -f {{.SecurityOptions}}\n14.999  runc             467722 1599     0 /usr/bin/runc --version\n15.002  docker-init      467733 1599     0 /usr/bin/docker-init --version\n15.011  runc             467739 1599     0 /usr/bin/runc --version\n15.014  docker-init      467745 1599     0 /usr/bin/docker-init --version\n15.023  rustup           467748 467535   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.029  rustup           467757 467535   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.037  rustup           467766 467548   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.043  rustup           467775 467548   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.053  rustup           467784 467535   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.067  rustup           467793 467548   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.077  uname            467802 467535   0 /usr/bin/uname -r\n15.090  uname            467803 467548   0 /usr/bin/uname -r\n15.094  docker           467804 467535   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.107  docker           467814 467548   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.142  systemd-sysctl   467830 467828   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha60e121 --prefix=/net/ipv4/neigh/vetha60e121 --prefix=/net/ipv6/conf/vetha60e121 --prefix=/net/ipv6/neigh/vetha60e121\n15.144  systemd-sysctl   467831 467829   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5d6981e --prefix=/net/ipv4/neigh/veth5d6981e --prefix=/net/ipv6/conf/veth5d6981e --prefix=/net/ipv6/neigh/veth5d6981e\n15.161  containerd-shim  467867 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee start\n15.161  systemd-sysctl   467866 467842   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth00063ae --prefix=/net/ipv4/neigh/veth00063ae --prefix=/net/ipv6/conf/veth00063ae --prefix=/net/ipv6/neigh/veth00063ae\n15.163  systemd-sysctl   467871 467853   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth40e6fa1 --prefix=/net/ipv4/neigh/veth40e6fa1 --prefix=/net/ipv6/conf/veth40e6fa1 --prefix=/net/ipv6/neigh/veth40e6fa1\n15.165  containerd-shim  467875 467867   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee -address /var/run/docker/containerd/containerd.sock\n15.168  runc             467884 467875   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee\n15.173  containerd-shim  467890 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 start\n15.177  exe              467899 467884   0 /proc/self/exe init\n15.179  containerd-shim  467900 467890   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 -address /var/run/docker/containerd/containerd.sock\n15.182  runc             467912 467900   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490\n15.187  exe              467920 467912   0 /proc/self/exe init\n15.212  exe              467936 467884   0 /proc/1599/exe -exec-root=/var/run/docker a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee d7da31e8f8e1\n15.213  exe              467937 467912   0 /proc/1599/exe -exec-root=/var/run/docker 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490 d7da31e8f8e1\n15.233  exe              467952 1599     0 /proc/self/exe /var/run/docker/netns/67593d8830ed all false\n15.233  exe              467953 1599     0 /proc/self/exe /var/run/docker/netns/3c05773b9ce6 all false\n15.432  runc             467990 467900   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d --log-format json --systemd-cgroup start 797dd10522acc8d9a0ae4237bf2cbffca4862aa483fe0b1028a7303801d56490\n15.433  runc             467991 467875   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2 --log-format json --systemd-cgroup start a09e081b03c8c9ca25dd65ba2688978a6835506b3e37ddf340408af50b2dafee\n15.438  sh               467930 467900   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.439  sh               467923 467875   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.439  cargo            468002 467930   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n15.440  cargo            468003 467923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.450  cargo-native-tr  468003 467923   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.451  cargo-native-tr  468002 467930   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n15.454  cargo            468004 468003   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.454  cargo            468005 468002   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.465  rustc            468006 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.465  rustc            468007 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.477  rustc            468010 468004   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.477  rustc            468011 468005   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.491  execsnoop        468018 468002   0 /usr/local/bin/execsnoop -t\n15.491  python3          468018 468002   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.492  execsnoop        468021 468003   0 /usr/local/bin/execsnoop -t\n15.492  python3          468021 468003   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.986  runc             468024 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2801572281 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n15.992  exe              468031 468024   0 /proc/self/exe init\n16.009  curl             468034 468024   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n16.243  sh               468040 2147557   0 /bin/sh -c which ps\n16.244  which            468040 2147557   0 /usr/bin/which ps\n16.246  sh               468041 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.248  ps               468041 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.274  sh               468042 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.276  cpuUsage.sh      468042 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.277  sed              468043 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.279  cat              468044 468042   0 /usr/bin/cat /proc/2240539/stat\n16.281  cat              468045 468042   0 /usr/bin/cat /proc/4193716/stat\n16.282  sleep            468046 468042   0 /usr/bin/sleep 1\n17.284  sed              468047 468042   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.286  cat              468048 468042   0 /usr/bin/cat /proc/2240539/stat\n17.288  cat              468050 468042   0 /usr/bin/cat /proc/4193716/stat\n17.356  cargo            468052 468002   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.369  rustc            468053 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.388  rustc            468059 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n17.431  cc               468079 468059   0 /tmp/native-trace-468002-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n17.432  cc               468080 468079   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcgzwtZ7/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1ldg12h.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1ldg12h.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n17.435  collect2         468081 468080   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.436  ld.lld           468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n17.438  rust-lld         468082 468081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1EQpd.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.474  build-script-bu  468100 468052   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n17.479  rustc            468102 468052   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=01dbfa75f86e934e ...\n17.627  cargo            468109 468003   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n17.640  rustc            468110 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.659  rustc            468116 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=471bea97ac833ce7 ...\n17.681  runc             468120 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup kill --all c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 9\n17.699  runc             468143 427985   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d --log-format json --systemd-cgroup delete c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n17.701  cc               468142 468116   0 /tmp/native-trace-468003-1783994537119/shims/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n17.702  cc               468149 468142   0 /usr/bin/cc -m64 /target/debug/build/current_platform-a964217115c09aba/rustcPFsIvp/symbols.o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.036romf6jsfwzkhgwh8nt5v5i.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.0qf7g6a66lhvugeg25fmxhmpz.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.1cdbnqkne1uue2w3ugcqeduul.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2ksqupl1p3172fjnu4j2tj7ht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.3hlqbfyscfg5b3iiwdsd53kpu.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4a2oqv8unsyj91o70xlpjqoeo.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.4g8mvet6hv1mk7qh0jyec20nd.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5b2yzufi9dfwwpn5uorhqq7hk.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.5sj7jievj38wdkrxmo0em406c.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6p5r2eb8hah2gpr478s6xdyht.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.6yd0rz80phram3vydfzrdq2bh.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.85uhmirg6s99udy2u60odgh3s.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cbx1gzkx8ugqceiazqfqzrek0.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.cuvulkrn1jpclenlfh1mqsd44.1vyb0jv.rcgu /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba.2quc5vzdaqy8kml17hwic0fg5.1vyb0jv.rcgu -Wl,--as-needed -Wl,-Bstatic ...\n17.705  collect2         468150 468149   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.706  ld.lld           468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/current_platform-a964217115c09aba/build_script_build-a964217115c09aba ...\n17.708  rust-lld         468151 468150   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxytDRW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.752  build-script-bu  468169 468109   0 /target/debug/build/current_platform-a964217115c09aba/build-script-build\n17.758  rustc            468171 468109   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name current_platform --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=eb508d71aca425cd ...\n17.894  containerd-shim  468178 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91d delete\n17.896  runc             468184 468178   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b7 --log-format json delete --force c1ad657b664d86d918cbd3009509467670a085754e478bc7b05f174f91da2b77\n17.957  systemd-sysctl   468190 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth26ae1bd --prefix=/net/ipv4/neigh/veth26ae1bd --prefix=/net/ipv6/conf/veth26ae1bd --prefix=/net/ipv6/neigh/veth26ae1bd\n17.968  runc             468191 461041   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb --log-format json --systemd-cgroup kill --all 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468 9\n17.985  runc             468197 461041   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb --log-format json --systemd-cgroup delete 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468\n18.190  containerd-shim  468203 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cb delete\n18.192  runc             468209 468203   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed46 --log-format json delete --force 93b14b32fa29069891455925d1484a4d8272806f5b88d3821dc0522b7cbed468\n18.232  sh               468217 467838   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth83795da\n18.233  ethtool          468218 468217   0 /usr/sbin/ethtool -i veth83795da\n18.234  sed              468219 468217   0 /usr/bin/sed -n s/^driver: //p\n18.239  systemd-sysctl   468222 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth83795da --prefix=/net/ipv4/neigh/veth83795da --prefix=/net/ipv6/conf/veth83795da --prefix=/net/ipv6/neigh/veth83795da\n18.386  runc             468224 461102   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c --log-format json --systemd-cgroup kill --all aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358 9\n18.404  runc             468230 461102   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c --log-format json --systemd-cgroup delete aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358\n18.484  runc             468236 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process812323305 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n18.489  exe              468243 468236   0 /proc/self/exe init\n18.498  curl             468245 468236   0 /usr/bin/curl -f http://localhost:9091/healthz\n18.580  containerd-shim  468252 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c delete\n18.582  runc             468259 468252   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a35 --log-format json delete --force aed2b1dcfee0a4592b8fd3a6450a6d6c963f26f92b66a22423a08b1ec6c5a358\n18.626  systemd-sysctl   468264 467838   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth61a52e7 --prefix=/net/ipv4/neigh/veth61a52e7 --prefix=/net/ipv6/conf/veth61a52e7 --prefix=/net/ipv6/neigh/veth61a52e7\n"
    },
    {
      "argv": [
        "/target/debug/build/substring-049b5fca247331ec/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463392,
      "build_script_target_dir": "substring-049b5fca247331ec",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/substring-049b5fca247331ec/build-script-build",
      "pid": 463392,
      "ppid": 462636,
      "root_cargo_pid": 462636,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463392,
      "build_script_target_dir": "substring-049b5fca247331ec",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 463394,
      "ppid": 463392,
      "root_cargo_pid": 462636,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_e188066370c82351_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/substring-85ebc2609a4e6a65/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463392,
      "build_script_target_dir": "substring-049b5fca247331ec",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 463402,
      "ppid": 463392,
      "root_cargo_pid": 462636,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "substring",
      "cwd": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "event_id": "bsrun:0b51861e31765141:bebeb726cf26c996:0b6d9a1c468b957a",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/substring-049b5fca247331ec/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
      "out_dir": "/target/debug/build/substring-049b5fca247331ec/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
      "success": true,
      "target": null,
      "version": "1.4.5",
      "_owner": {
        "crate": "substring",
        "version": "1.4.5",
        "package_id": "path+file:///tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5#substring@1.4.5",
        "manifest_dir": "/tmp/crate-build-riscv64-ql9j87rr/src/substring-1.4.5",
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
      "build_script_root_pid": 463392,
      "build_script_target_dir": "substring-049b5fca247331ec",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 463394,
      "ppid": 463392,
      "root_cargo_pid": 462636,
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
        "autocfg_e188066370c82351_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/substring-85ebc2609a4e6a65/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 463392,
      "build_script_target_dir": "substring-049b5fca247331ec",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 463402,
      "ppid": 463392,
      "root_cargo_pid": 462636,
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
