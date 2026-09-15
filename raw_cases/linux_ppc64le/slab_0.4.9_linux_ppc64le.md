# `slab` `0.4.9`

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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
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
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21",
    "/target/debug/build/slab-b0fe9ec70d8d0253",
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
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-18016-1783992650997570030.map",
  "pid": 18016,
  "ppid": 18000,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-18016-1783992650997570030.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "workspace_root": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.23",
      "name": "rustversion",
      "version": "1.0.23",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_test@1.0.177",
      "name": "serde_test",
      "version": "1.0.177",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177"
    },
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
      "name": "slab",
      "version": "0.4.9",
      "manifest_path": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
      "name": "syn",
      "version": "2.0.118",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
      "name": "unicode-ident",
      "version": "1.0.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
    }
  ],
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "exit_code": 0,
  "kind": "exec",
  "pid": 18016,
  "ppid": 18000,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "event_id": "used:cc:c4182b286e25dd37:ef6340d6a37de610:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
  "pid": 18016,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "event_id": "used:cc:c4182b286e25dd37:68bdedc7f6698cae:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
  "pid": 18016,
  "sha256": "ec9386980024dfb18d7e7fb45b805ab059e66741b0c9204062ae4e66bafa3852",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "event_id": "used:cc:c4182b286e25dd37:afe33d5e4cdf9535:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
  "pid": 18016,
  "sha256": "059de519b74a1011d8e29868af293228e8bc6e7c093eba8ff439c5d2c02886c2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "event_id": "used:cc:c4182b286e25dd37:fc86d25d8c3075df:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
  "pid": 18016,
  "sha256": "736b61140e2bf0e5327b7e67b659b2504493cb311ae01d0914515153d9e9e13a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "event_id": "used:cc:c4182b286e25dd37:022ce81717081884:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
  "pid": 18016,
  "sha256": "219be961590e1f4123771488cddf662266a7c9c170b78e73e48893f4715f898b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "event_id": "used:cc:c4182b286e25dd37:acd961252cfed4f2:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
  "pid": 18016,
  "sha256": "8e38ca3fcca173a9d5417ba1348a864ab4d1a249fe40cd7e4f78cfb5ee333ee1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "event_id": "used:cc:c4182b286e25dd37:1af430753ef4921b:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
  "pid": 18016,
  "sha256": "e721e7da3f2cd9ccfdca2c3691109f4f1c5b212b482fe3ed26ca86be3a7565f0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "event_id": "used:cc:c4182b286e25dd37:c823c0e5ef69bd57:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
  "pid": 18016,
  "sha256": "7530fad916cbecc21bc22027ec27cba35ea6182851d1de0b5b60e427225c6ff3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "event_id": "used:cc:c4182b286e25dd37:b15fc61fc2d97de0:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
  "pid": 18016,
  "sha256": "99a34633d6033b1d9171dc57bc47506d4f115b74ba18fa88df331b84c096145b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "event_id": "used:cc:c4182b286e25dd37:c3b47f5471a4b0b7:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
  "pid": 18016,
  "sha256": "d8ba05431cccf258e5dc8aca11279a7038deed1ae36828c3efa3f6365cb14165",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
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
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "context_path": "/tmp/native-trace-16320-1783992647571/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-16320-1783992647571/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 18016,
  "ppid": 18000,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 15

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21",
    "/target/debug/build/slab-b0fe9ec70d8d0253",
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
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-18016-1783992650997570030.map",
  "pid": 18016,
  "ppid": 18000,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-18016-1783992650997570030.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
    "source": "cargo_manifest_dir"
  }
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

#### Record 17

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 264,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 266,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n1.795   sh               18967  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n1.797   cpuUsage.sh      18967  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n1.801   sed              18973  18967    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n1.802   cat              18977  18967    0 /usr/bin/cat /proc/2240539/stat\n1.804   cat              18982  18967    0 /usr/bin/cat /proc/4193716/stat\n1.808   sleep            18987  18967    0 /usr/bin/sleep 1\n1.844   cc               19031  18600    0 /tmp/native-trace-16589-1783992647867/shims/cc -Wl,--version-script=/target/debug/deps/rustcHxgLCt/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHxgLCt/symbols.o /target/debug/deps/paste-2e3fe426df155f13.0ilvpcltyotio7f5zb6yr8bu0.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0jpbko25wyvbn1t2yyoj1rnm3.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0mf6buqe6ku65te2vt9vh16ew.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rd4pbcoza8yj2ekmclz4q2xd.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rhmlpaa4diu28hpn1a64cmst.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rle0e738cqic5jqjcr0jbkv0.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1c8npid0kxj6rc9o7lh0frz59.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1e4uiaqa8jsn9jt4qa2xqte0s.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1mz4vi1u2tp23a7x1c8rjiw59.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1yjwjq7lr38ardlt4zvywxbdm.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1zqshansne11y4p1f3gkrdxgc.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2107gqfzru357abk16hy2olyn.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2f14ilwoct35pgrlrhg9chsmn.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2kywatxh8geyarz4hnyjwnz2z.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2ofux8kbhp52j2xnc6hy54ygm.0bg00n5.rcgu.o ...\n1.846   cc               19044  19031    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcHxgLCt/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHxgLCt/symbols.o /target/debug/deps/paste-2e3fe426df155f13.0ilvpcltyotio7f5zb6yr8bu0.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0jpbko25wyvbn1t2yyoj1rnm3.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0mf6buqe6ku65te2vt9vh16ew.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rd4pbcoza8yj2ekmclz4q2xd.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rhmlpaa4diu28hpn1a64cmst.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rle0e738cqic5jqjcr0jbkv0.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1c8npid0kxj6rc9o7lh0frz59.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1e4uiaqa8jsn9jt4qa2xqte0s.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1mz4vi1u2tp23a7x1c8rjiw59.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1yjwjq7lr38ardlt4zvywxbdm.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1zqshansne11y4p1f3gkrdxgc.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2107gqfzru357abk16hy2olyn.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2f14ilwoct35pgrlrhg9chsmn.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2kywatxh8geyarz4hnyjwnz2z.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2ofux8kbhp52j2xnc6hy54ygm.0bg00n5.rcgu.o ...\n1.852   collect2         19050  19044    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKOH3Od.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcHxgLCt/raw-dylibs ...\n1.854   ld.lld           19052  19050    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKOH3Od.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcHxgLCt/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n1.858   rust-lld         19052  19050    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKOH3Od.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n1.866   cc               19062  18623    0 /tmp/native-trace-16492-1783992647709/shims/cc -Wl,--version-script=/target/debug/deps/rustc1WmvvL/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc1WmvvL/symbols.o /target/debug/deps/paste-2e3fe426df155f13.0ilvpcltyotio7f5zb6yr8bu0.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0jpbko25wyvbn1t2yyoj1rnm3.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0mf6buqe6ku65te2vt9vh16ew.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rd4pbcoza8yj2ekmclz4q2xd.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rhmlpaa4diu28hpn1a64cmst.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rle0e738cqic5jqjcr0jbkv0.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1c8npid0kxj6rc9o7lh0frz59.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1e4uiaqa8jsn9jt4qa2xqte0s.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1mz4vi1u2tp23a7x1c8rjiw59.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1yjwjq7lr38ardlt4zvywxbdm.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1zqshansne11y4p1f3gkrdxgc.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2107gqfzru357abk16hy2olyn.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2f14ilwoct35pgrlrhg9chsmn.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2kywatxh8geyarz4hnyjwnz2z.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2ofux8kbhp52j2xnc6hy54ygm.1ewszkc.rcgu.o ...\n1.868   cc               19067  19062    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc1WmvvL/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc1WmvvL/symbols.o /target/debug/deps/paste-2e3fe426df155f13.0ilvpcltyotio7f5zb6yr8bu0.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0jpbko25wyvbn1t2yyoj1rnm3.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0mf6buqe6ku65te2vt9vh16ew.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rd4pbcoza8yj2ekmclz4q2xd.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rhmlpaa4diu28hpn1a64cmst.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rle0e738cqic5jqjcr0jbkv0.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1c8npid0kxj6rc9o7lh0frz59.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1e4uiaqa8jsn9jt4qa2xqte0s.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1mz4vi1u2tp23a7x1c8rjiw59.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1yjwjq7lr38ardlt4zvywxbdm.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1zqshansne11y4p1f3gkrdxgc.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2107gqfzru357abk16hy2olyn.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2f14ilwoct35pgrlrhg9chsmn.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2kywatxh8geyarz4hnyjwnz2z.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2ofux8kbhp52j2xnc6hy54ygm.1ewszkc.rcgu.o ...\n1.873   collect2         19074  19067    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp74fGY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc1WmvvL/raw-dylibs ...\n1.875   ld.lld           19076  19074    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp74fGY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc1WmvvL/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n1.877   rust-lld         19076  19074    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp74fGY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n2.261   cargo            19194  17317    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n2.274   rustc            19195  19194    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.294   rustc            19201  19194    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=17ea78e1f68348d9 ...\n2.348   cc               19222  19201    0 /tmp/native-trace-17317-1783992649178/shims/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustc7iuoRk/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.15cb2bl.rc -Wl,--as-needed ...\n2.350   cc               19223  19222    0 /usr/bin/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustc7iuoRk/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.15cb2bl.rc -Wl,--as-needed ...\n2.353   collect2         19224  19223    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgd3ahJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.355   ld.lld           19225  19224    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgd3ahJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc ...\n2.357   rust-lld         19225  19224    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgd3ahJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.380   cargo            19242  17147    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n2.393   rustc            19243  19242    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.397   build-script-bu  19245  19194    0 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build-script-build\n2.401   rustc            19247  19194    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_x86_64_gnu --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=10cda3178906b4b0 ...\n2.410   rustc            19253  19242    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=17ea78e1f68348d9 ...\n2.456   cc               19280  19253    0 /tmp/native-trace-17147-1783992649006/shims/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustcpYh7cU/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.16e9bd8.rc -Wl,--as-needed ...\n2.457   cc               19281  19280    0 /usr/bin/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustcpYh7cU/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.16e9bd8.rc -Wl,--as-needed ...\n2.460   collect2         19282  19281    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHvuDiv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.461   ld.lld           19283  19282    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHvuDiv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc ...\n2.463   rust-lld         19283  19282    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHvuDiv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.499   build-script-bu  19301  19242    0 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build-script-build\n2.504   rustc            19303  19242    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_x86_64_gnu --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=777b52e33faa79e7 ...\n2.585   cargo            19310  17617    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n2.599   rustc            19311  19310    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.617   rustc            19317  19310    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=17ea78e1f68348d9 ...\n2.666   cc               19338  19317    0 /tmp/native-trace-17617-1783992649660/shims/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustchrfCNS/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.19f12vc.rc -Wl,--as-needed ...\n2.668   cc               19339  19338    0 /usr/bin/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustchrfCNS/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.19f12vc.rc -Wl,--as-needed ...\n2.671   collect2         19340  19339    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDRIAmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.673   ld.lld           19341  19340    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDRIAmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc ...\n2.674   rust-lld         19341  19340    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDRIAmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.679   cargo            19342  17379    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n2.692   rustc            19359  19342    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.709   rustc            19365  19342    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=31da43351054ee1b ...\n2.715   build-script-bu  19367  19310    0 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build-script-build\n2.720   rustc            19372  19310    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_x86_64_gnu --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=5f38fecf9c151804 ...\n2.751   cc               19396  19365    0 /tmp/native-trace-17379-1783992649314/shims/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustcWyocFT/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.140ug1a. -Wl,--as-needed ...\n2.752   cc               19397  19396    0 /usr/bin/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustcWyocFT/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.140ug1a. -Wl,--as-needed ...\n2.755   collect2         19398  19397    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7qdSBn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.756   ld.lld           19399  19398    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7qdSBn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761 ...\n2.758   rust-lld         19399  19398    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7qdSBn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.794   build-script-bu  19417  19342    0 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build-script-build\n2.799   rustc            19419  19342    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_aarch64_msvc --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=152233d675c7bc45 ...\n2.810   sed              19423  18967    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n2.813   cat              19424  18967    0 /usr/bin/cat /proc/2240539/stat\n2.815   cat              19426  18967    0 /usr/bin/cat /proc/4193716/stat\n2.882   cargo            19431  17845    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n2.884   cargo            19432  17835    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n2.895   rustc            19433  19431    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.898   rustc            19434  19432    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.914   rustc            19445  19432    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=31da43351054ee1b ...\n2.914   rustc            19446  19431    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=31da43351054ee1b ...\n2.955   cc               19487  19445    0 /tmp/native-trace-17835-1783992650239/shims/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustcgE0T9z/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.10rf04z. -Wl,--as-needed ...\n2.956   cc               19489  19487    0 /usr/bin/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustcgE0T9z/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.10rf04z. -Wl,--as-needed ...\n2.956   cc               19488  19446    0 /tmp/native-trace-17845-1783992650282/shims/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustch7kxj2/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.1ga7v1e. -Wl,--as-needed ...\n2.957   cc               19490  19488    0 /usr/bin/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustch7kxj2/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.1ga7v1e. -Wl,--as-needed ...\n2.959   collect2         19491  19489    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOLJxkQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.960   collect2         19492  19490    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUIDhKW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.961   ld.lld           19493  19491    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOLJxkQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761 ...\n2.962   ld.lld           19494  19492    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUIDhKW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761 ...\n2.962   rust-lld         19493  19491    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOLJxkQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.964   rust-lld         19494  19492    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUIDhKW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.998   build-script-bu  19529  19432    0 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build-script-build\n2.998   build-script-bu  19530  19431    0 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build-script-build\n3.003   rustc            19533  19432    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_aarch64_msvc --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=7ca1212926e48158 ...\n3.003   rustc            19534  19431    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_aarch64_msvc --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0c49ab467ef3eabe ...\n6.745   sh               19547  2147557   0 /bin/sh -c which ps\n6.747   which            19547  2147557   0 /usr/bin/which ps\n6.749   sh               19548  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n6.751   ps               19548  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n6.783   sh               19549  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n6.785   cpuUsage.sh      19549  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n6.786   sed              19550  19549    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n6.789   cat              19551  19549    0 /usr/bin/cat /proc/2240539/stat\n6.790   cat              19552  19549    0 /usr/bin/cat /proc/4193716/stat\n6.791   sleep            19553  19549    0 /usr/bin/sleep 1\n7.795   sed              19554  19549    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n7.798   cat              19555  19549    0 /usr/bin/cat /proc/2240539/stat\n7.800   cat              19557  19549    0 /usr/bin/cat /proc/4193716/stat\n8.965   runc             19560  4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1817811637 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n8.972   exe              19567  19560    0 /proc/self/exe init\n8.990   curl             19570  19560    0 /usr/bin/curl -f http://localhost:9091/healthz\n14.022  16               19577  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n14.043  frpc             19577  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n15.941  runc             19584  3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2708877818 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n15.948  exe              19591  19584    0 /proc/self/exe init\n15.968  curl             19593  19584    0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n16.571  16               19600  1        0 /proc/self/fd/16 --deserialize 155 --log-level info --log-target journal-or-kmsg\n16.574  16               19601  1        0 /proc/self/fd/16 --deserialize 182 --log-level info --log-target journal-or-kmsg\n16.739  drkonqi-coredum  19601  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 883-19599-0\n16.744  systemd-coredum  19600  1        0 /usr/lib/systemd/systemd-coredump\n17.274  9                19613  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n17.279  abrt-server      19614  1118     0 /usr/bin/abrt-server -s\n17.292  drkonqi-coredum  19613  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n17.309  abrt-handle-eve  19615  19614    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:31:07.647632-13977\n17.324  runc             19618  15780    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d9 --log-format json --systemd-cgroup kill --all 014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d994e93 9\n17.328  sh               19627  19615    0 /bin/sh -c abrt-action-save-package-data\\n\n17.329  abrt-action-sav  19627  19615    0 /usr/bin/abrt-action-save-package-data\n17.333  runc             19628  15780    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d9 --log-format json --systemd-cgroup delete 014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d994e93\n17.393  sh               19634  19615    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n17.395  cut              19636  19634    0 /usr/bin/cut -d: -f1\n17.395  cat              19637  19635    0 /usr/bin/cat uid\n17.396  getent           19635  19634    0 /usr/bin/getent passwd 1000\n17.397  lscpu            19638  19634    0 /usr/bin/lscpu\n17.414  sh               19639  19615    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n17.416  runlevel         19640  19639    0 /usr/bin/runlevel\n17.427  sh               19641  19615    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n17.429  grep             19642  19641    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n17.431  grep             19643  19641    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n17.432  grep             19644  19641    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n17.434  abrt-action-cor  19645  19641    0 /usr/libexec/abrt-action-coredump -x\n17.456  runc             19647  16017    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764 --log-format json --systemd-cgroup kill --all 9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764336d4 9\n17.464  runc             19653  16017    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764 --log-format json --systemd-cgroup delete 9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764336d4\n17.504  abrt-action-gen  19659  19641    0 /usr/bin/abrt-action-generate-core-backtrace\n17.548  containerd-shim  19660  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d994e93 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d9 delete\n17.551  runc             19666  19660    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d994e9 --log-format json delete --force 014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d994e93\n17.576  abrt-action-ana  19672  19641    0 /usr/bin/abrt-action-analyze-vulnerability\n17.578  eu-readelf       19674  19673    0 /usr/bin/eu-readelf -n coredump\n17.579  sed              19676  19673    0 /usr/bin/sed s/[^0-9]//g\n17.579  grep             19675  19673    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n17.581  gdb              19678  19677    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n17.594  sh               19682  19679    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth53801cd\n17.595  ethtool          19683  19682    0 /usr/sbin/ethtool -i veth53801cd\n17.595  sed              19684  19682    0 /usr/bin/sed -n s/^driver: //p\n17.599  iconv            19687  19678    0 /usr/bin/iconv -l\n17.603  systemd-sysctl   19688  19679    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth53801cd --prefix=/net/ipv4/neigh/veth53801cd --prefix=/net/ipv6/conf/veth53801cd --prefix=/net/ipv6/neigh/veth53801cd\n17.677  containerd-shim  19698  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764336d4 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764 delete\n17.681  runc             19705  19698    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764336d --log-format json delete --force 9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764336d4\n17.703  abrt-action-ana  19710  19641    0 /usr/bin/abrt-action-analyze-c\n17.713  systemd-sysctl   19711  19679    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth169ae7b --prefix=/net/ipv4/neigh/veth169ae7b --prefix=/net/ipv6/conf/veth169ae7b --prefix=/net/ipv6/neigh/veth169ae7b\n17.717  eu-unstrip       19712  19710    0 /usr/bin/eu-unstrip --core=./coredump -n\n17.737  abrt-action-lis  19714  19641    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n17.803  cat              19716  19715    0 /usr/bin/cat executable\n17.805  cat              19717  19715    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:31:07.647632-13977/uid\n17.806  journalctl       19718  19715    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n17.820  abrt-action-cor  19719  19641    0 /usr/libexec/abrt-action-coredump -r\n17.881  abrt-handle-eve  19720  19614    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.898  sh               19721  19720    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n17.900  dbus-send        19721  19720    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.902  sh               19722  19720    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n17.903  abrt-action-not  19723  19722    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.975  sh               19724  19723    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n17.977  reporter-system  19724  19723    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n"
}
```

#### Record 18

```json
{
  "argv": [
    "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 18054,
  "build_script_target_dir": "slab-b0fe9ec70d8d0253",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build",
  "pid": 18054,
  "ppid": 17898,
  "root_cargo_pid": 17898,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "_build_script_out_dir": "/target/debug/build/slab-b0fe9ec70d8d0253/out"
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
  "build_script_root_pid": 18054,
  "build_script_target_dir": "slab-b0fe9ec70d8d0253",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 18055,
  "ppid": 18054,
  "root_cargo_pid": 17898,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "_build_script_out_dir": "/target/debug/build/slab-b0fe9ec70d8d0253/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 20

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_1d4b08aa5482ae09_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/slab-3ef8dc27102d261a/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 18054,
  "build_script_target_dir": "slab-b0fe9ec70d8d0253",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 18060,
  "ppid": 18054,
  "root_cargo_pid": 17898,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "_build_script_out_dir": "/target/debug/build/slab-b0fe9ec70d8d0253/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 21

```json
{
  "crate": "slab",
  "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "event_id": "bsrun:43852cb09115910d:66f198e27447f3ac:8b19fa83fcf83981",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
  "out_dir": "/target/debug/build/slab-b0fe9ec70d8d0253/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
  "success": true,
  "target": null,
  "version": "0.4.9",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
    "source": "cwd_prefix"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 18054,
  "build_script_target_dir": "slab-b0fe9ec70d8d0253",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 18055,
  "ppid": 18054,
  "root_cargo_pid": 17898,
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
    "--crate-name",
    "autocfg_1d4b08aa5482ae09_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/slab-3ef8dc27102d261a/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 18054,
  "build_script_target_dir": "slab-b0fe9ec70d8d0253",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 18060,
  "ppid": 18054,
  "root_cargo_pid": 17898,
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
  "time": "2026-07-14T01:31:08.685483+00:00",
  "crate": "slab",
  "version": "0.4.9",
  "architecture": "ppc64le",
  "duration_seconds": 27.100807414855808,
  "trace_record_count": 21,
  "trace_owner_summary": {
    "owner_package_count": 11,
    "owner_packages": [
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
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml"
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
        "crate": "serde_test",
        "version": "1.0.177",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_test@1.0.177",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.118",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml"
      },
      {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "manifest_path": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9/Cargo.toml"
      }
    ],
    "attributed_event_count": 16,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "slab",
        "version": "0.4.9",
        "event_count": 16,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 10,
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
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "workspace_root": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustversion@1.0.23",
          "name": "rustversion",
          "version": "1.0.23",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustversion-1.0.23"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_test@1.0.177",
          "name": "serde_test",
          "version": "1.0.177",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.177"
        },
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
          "name": "slab",
          "version": "0.4.9",
          "manifest_path": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
          "name": "syn",
          "version": "2.0.118",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
          "name": "unicode-ident",
          "version": "1.0.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
        }
      ],
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "exit_code": 0,
      "kind": "exec",
      "pid": 18016,
      "ppid": 18000,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "event_id": "used:cc:c4182b286e25dd37:ef6340d6a37de610:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
      "pid": 18016,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "event_id": "used:cc:c4182b286e25dd37:68bdedc7f6698cae:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
      "pid": 18016,
      "sha256": "ec9386980024dfb18d7e7fb45b805ab059e66741b0c9204062ae4e66bafa3852",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "event_id": "used:cc:c4182b286e25dd37:afe33d5e4cdf9535:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
      "pid": 18016,
      "sha256": "059de519b74a1011d8e29868af293228e8bc6e7c093eba8ff439c5d2c02886c2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "event_id": "used:cc:c4182b286e25dd37:fc86d25d8c3075df:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
      "pid": 18016,
      "sha256": "736b61140e2bf0e5327b7e67b659b2504493cb311ae01d0914515153d9e9e13a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "event_id": "used:cc:c4182b286e25dd37:022ce81717081884:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
      "pid": 18016,
      "sha256": "219be961590e1f4123771488cddf662266a7c9c170b78e73e48893f4715f898b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "event_id": "used:cc:c4182b286e25dd37:acd961252cfed4f2:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
      "pid": 18016,
      "sha256": "8e38ca3fcca173a9d5417ba1348a864ab4d1a249fe40cd7e4f78cfb5ee333ee1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "event_id": "used:cc:c4182b286e25dd37:1af430753ef4921b:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
      "pid": 18016,
      "sha256": "e721e7da3f2cd9ccfdca2c3691109f4f1c5b212b482fe3ed26ca86be3a7565f0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "event_id": "used:cc:c4182b286e25dd37:c823c0e5ef69bd57:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
      "pid": 18016,
      "sha256": "7530fad916cbecc21bc22027ec27cba35ea6182851d1de0b5b60e427225c6ff3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "event_id": "used:cc:c4182b286e25dd37:b15fc61fc2d97de0:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
      "pid": 18016,
      "sha256": "99a34633d6033b1d9171dc57bc47506d4f115b74ba18fa88df331b84c096145b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "event_id": "used:cc:c4182b286e25dd37:c3b47f5471a4b0b7:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
      "pid": 18016,
      "sha256": "d8ba05431cccf258e5dc8aca11279a7038deed1ae36828c3efa3f6365cb14165",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
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
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "context_path": "/tmp/native-trace-16320-1783992647571/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-16320-1783992647571/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 18016,
      "ppid": 18000,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21",
        "/target/debug/build/slab-b0fe9ec70d8d0253",
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
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcCX8X21/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0y8ozgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0y8ozgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0y8ozgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0y8ozgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0y8ozgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0y8ozgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0y8ozgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0y8ozgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0y8ozgr.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-18016-1783992650997570030.map",
      "pid": 18016,
      "ppid": 18000,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-18016-1783992650997570030.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
      "parsed_event_count": 264,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 266,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n1.795   sh               18967  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n1.797   cpuUsage.sh      18967  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n1.801   sed              18973  18967    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n1.802   cat              18977  18967    0 /usr/bin/cat /proc/2240539/stat\n1.804   cat              18982  18967    0 /usr/bin/cat /proc/4193716/stat\n1.808   sleep            18987  18967    0 /usr/bin/sleep 1\n1.844   cc               19031  18600    0 /tmp/native-trace-16589-1783992647867/shims/cc -Wl,--version-script=/target/debug/deps/rustcHxgLCt/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHxgLCt/symbols.o /target/debug/deps/paste-2e3fe426df155f13.0ilvpcltyotio7f5zb6yr8bu0.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0jpbko25wyvbn1t2yyoj1rnm3.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0mf6buqe6ku65te2vt9vh16ew.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rd4pbcoza8yj2ekmclz4q2xd.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rhmlpaa4diu28hpn1a64cmst.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rle0e738cqic5jqjcr0jbkv0.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1c8npid0kxj6rc9o7lh0frz59.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1e4uiaqa8jsn9jt4qa2xqte0s.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1mz4vi1u2tp23a7x1c8rjiw59.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1yjwjq7lr38ardlt4zvywxbdm.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1zqshansne11y4p1f3gkrdxgc.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2107gqfzru357abk16hy2olyn.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2f14ilwoct35pgrlrhg9chsmn.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2kywatxh8geyarz4hnyjwnz2z.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2ofux8kbhp52j2xnc6hy54ygm.0bg00n5.rcgu.o ...\n1.846   cc               19044  19031    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcHxgLCt/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHxgLCt/symbols.o /target/debug/deps/paste-2e3fe426df155f13.0ilvpcltyotio7f5zb6yr8bu0.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0jpbko25wyvbn1t2yyoj1rnm3.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0mf6buqe6ku65te2vt9vh16ew.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rd4pbcoza8yj2ekmclz4q2xd.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rhmlpaa4diu28hpn1a64cmst.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rle0e738cqic5jqjcr0jbkv0.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1c8npid0kxj6rc9o7lh0frz59.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1e4uiaqa8jsn9jt4qa2xqte0s.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1mz4vi1u2tp23a7x1c8rjiw59.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1yjwjq7lr38ardlt4zvywxbdm.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1zqshansne11y4p1f3gkrdxgc.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2107gqfzru357abk16hy2olyn.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2f14ilwoct35pgrlrhg9chsmn.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2kywatxh8geyarz4hnyjwnz2z.0bg00n5.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2ofux8kbhp52j2xnc6hy54ygm.0bg00n5.rcgu.o ...\n1.852   collect2         19050  19044    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKOH3Od.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcHxgLCt/raw-dylibs ...\n1.854   ld.lld           19052  19050    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKOH3Od.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcHxgLCt/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n1.858   rust-lld         19052  19050    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKOH3Od.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n1.866   cc               19062  18623    0 /tmp/native-trace-16492-1783992647709/shims/cc -Wl,--version-script=/target/debug/deps/rustc1WmvvL/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc1WmvvL/symbols.o /target/debug/deps/paste-2e3fe426df155f13.0ilvpcltyotio7f5zb6yr8bu0.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0jpbko25wyvbn1t2yyoj1rnm3.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0mf6buqe6ku65te2vt9vh16ew.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rd4pbcoza8yj2ekmclz4q2xd.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rhmlpaa4diu28hpn1a64cmst.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rle0e738cqic5jqjcr0jbkv0.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1c8npid0kxj6rc9o7lh0frz59.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1e4uiaqa8jsn9jt4qa2xqte0s.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1mz4vi1u2tp23a7x1c8rjiw59.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1yjwjq7lr38ardlt4zvywxbdm.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1zqshansne11y4p1f3gkrdxgc.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2107gqfzru357abk16hy2olyn.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2f14ilwoct35pgrlrhg9chsmn.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2kywatxh8geyarz4hnyjwnz2z.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2ofux8kbhp52j2xnc6hy54ygm.1ewszkc.rcgu.o ...\n1.868   cc               19067  19062    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc1WmvvL/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc1WmvvL/symbols.o /target/debug/deps/paste-2e3fe426df155f13.0ilvpcltyotio7f5zb6yr8bu0.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0jpbko25wyvbn1t2yyoj1rnm3.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0mf6buqe6ku65te2vt9vh16ew.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rd4pbcoza8yj2ekmclz4q2xd.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rhmlpaa4diu28hpn1a64cmst.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.0rle0e738cqic5jqjcr0jbkv0.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1c8npid0kxj6rc9o7lh0frz59.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1e4uiaqa8jsn9jt4qa2xqte0s.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1mz4vi1u2tp23a7x1c8rjiw59.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1yjwjq7lr38ardlt4zvywxbdm.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.1zqshansne11y4p1f3gkrdxgc.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2107gqfzru357abk16hy2olyn.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2f14ilwoct35pgrlrhg9chsmn.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2kywatxh8geyarz4hnyjwnz2z.1ewszkc.rcgu.o /target/debug/deps/paste-2e3fe426df155f13.2ofux8kbhp52j2xnc6hy54ygm.1ewszkc.rcgu.o ...\n1.873   collect2         19074  19067    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp74fGY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc1WmvvL/raw-dylibs ...\n1.875   ld.lld           19076  19074    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp74fGY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc1WmvvL/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n1.877   rust-lld         19076  19074    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccp74fGY.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libpaste-2e3fe426df155f13.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n2.261   cargo            19194  17317    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n2.274   rustc            19195  19194    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.294   rustc            19201  19194    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=17ea78e1f68348d9 ...\n2.348   cc               19222  19201    0 /tmp/native-trace-17317-1783992649178/shims/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustc7iuoRk/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.15cb2bl.rc -Wl,--as-needed ...\n2.350   cc               19223  19222    0 /usr/bin/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustc7iuoRk/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.15cb2bl.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.15cb2bl.rc -Wl,--as-needed ...\n2.353   collect2         19224  19223    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgd3ahJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.355   ld.lld           19225  19224    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgd3ahJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc ...\n2.357   rust-lld         19225  19224    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgd3ahJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.380   cargo            19242  17147    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n2.393   rustc            19243  19242    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.397   build-script-bu  19245  19194    0 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build-script-build\n2.401   rustc            19247  19194    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_x86_64_gnu --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=10cda3178906b4b0 ...\n2.410   rustc            19253  19242    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=17ea78e1f68348d9 ...\n2.456   cc               19280  19253    0 /tmp/native-trace-17147-1783992649006/shims/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustcpYh7cU/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.16e9bd8.rc -Wl,--as-needed ...\n2.457   cc               19281  19280    0 /usr/bin/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustcpYh7cU/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.16e9bd8.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.16e9bd8.rc -Wl,--as-needed ...\n2.460   collect2         19282  19281    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHvuDiv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.461   ld.lld           19283  19282    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHvuDiv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc ...\n2.463   rust-lld         19283  19282    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccHvuDiv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.499   build-script-bu  19301  19242    0 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build-script-build\n2.504   rustc            19303  19242    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_x86_64_gnu --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=777b52e33faa79e7 ...\n2.585   cargo            19310  17617    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n2.599   rustc            19311  19310    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.617   rustc            19317  19310    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=17ea78e1f68348d9 ...\n2.666   cc               19338  19317    0 /tmp/native-trace-17617-1783992649660/shims/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustchrfCNS/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.19f12vc.rc -Wl,--as-needed ...\n2.668   cc               19339  19338    0 /usr/bin/cc -m64 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/rustchrfCNS/symbols.o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.012c0a004lbgak33oupj8sv3h.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.0w887nn631llfsjmzpf6lqd0e.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.321xb8t6ybuu85cw8fgt5w1by.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.3lguqfxoe749v73x8y1289lm8.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.65jhhg0t619r1yrx5qlke4eb7.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7908z5xr139nftwj3snqryy9o.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.7ms80ubu3fq23b8ljr4kq4fgq.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.9miw1jkgcbxnd9r3rythqvhnd.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bg33960yrq5hl00bem71sj99e.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.bgwnhl1hhrh5j8iwjxp0c7p50.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cff4unychqizwfu4x7er9lps9.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.cq94lnjm7xwdytfswbg247c5l.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.crpfq9m5j6fdcr2adu459ba65.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.e5h1avc13ttqyzojbmef5jito.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.f4a3rhb8dyd1jmwps67uylsgj.19f12vc.rc /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc.701trp3f3vsbfskyn00doc0lg.19f12vc.rc -Wl,--as-needed ...\n2.671   collect2         19340  19339    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDRIAmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.673   ld.lld           19341  19340    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDRIAmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build_script_build-f94abb14b8be14bc ...\n2.674   rust-lld         19341  19340    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDRIAmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.679   cargo            19342  17379    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n2.692   rustc            19359  19342    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.709   rustc            19365  19342    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=31da43351054ee1b ...\n2.715   build-script-bu  19367  19310    0 /target/debug/build/windows_x86_64_gnu-f94abb14b8be14bc/build-script-build\n2.720   rustc            19372  19310    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_x86_64_gnu --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=5f38fecf9c151804 ...\n2.751   cc               19396  19365    0 /tmp/native-trace-17379-1783992649314/shims/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustcWyocFT/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.140ug1a. -Wl,--as-needed ...\n2.752   cc               19397  19396    0 /usr/bin/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustcWyocFT/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.140ug1a. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.140ug1a. -Wl,--as-needed ...\n2.755   collect2         19398  19397    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7qdSBn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.756   ld.lld           19399  19398    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7qdSBn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761 ...\n2.758   rust-lld         19399  19398    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7qdSBn.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.794   build-script-bu  19417  19342    0 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build-script-build\n2.799   rustc            19419  19342    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_aarch64_msvc --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=152233d675c7bc45 ...\n2.810   sed              19423  18967    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n2.813   cat              19424  18967    0 /usr/bin/cat /proc/2240539/stat\n2.815   cat              19426  18967    0 /usr/bin/cat /proc/4193716/stat\n2.882   cargo            19431  17845    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n2.884   cargo            19432  17835    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n2.895   rustc            19433  19431    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.898   rustc            19434  19432    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n2.914   rustc            19445  19432    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=31da43351054ee1b ...\n2.914   rustc            19446  19431    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=31da43351054ee1b ...\n2.955   cc               19487  19445    0 /tmp/native-trace-17835-1783992650239/shims/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustcgE0T9z/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.10rf04z. -Wl,--as-needed ...\n2.956   cc               19489  19487    0 /usr/bin/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustcgE0T9z/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.10rf04z. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.10rf04z. -Wl,--as-needed ...\n2.956   cc               19488  19446    0 /tmp/native-trace-17845-1783992650282/shims/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustch7kxj2/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.1ga7v1e. -Wl,--as-needed ...\n2.957   cc               19490  19488    0 /usr/bin/cc -m64 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/rustch7kxj2/symbols.o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0dnzbeb7qt0lmd5daqsc8qrmh.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0s33a6ggrkjyw0lrbnwgtnh4u.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.1zcaddirl75erm0ugp54lu4ny.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.2s3uyeyutz1ahkhf1tf6i4izw.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.34s8kc98skokd10g7sqd6iyii.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.3qllxnt9r4iynxvs014epmukw.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.4o9h2hseml7rn74l5ekgxw1jq.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.6ecqa5dkdbp91yvooaduczvwr.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.79oiom4caslexvwwblerhv3ba.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.7r5egfl8htta50basne6uc64m.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9k4l3bm23utwfoj2mxjoja61m.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.9zpy36lvb3in49ez4pniroxrb.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.am7ntt4ec7ekz1w1w1ec8qurt.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b57kiiqb7g1thyzja3zrg4h8x.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.b88x0tnla05sb01ui5lx0yvyi.1ga7v1e. /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761.0cbjr0o8ahsvl8zl9csnvggp4.1ga7v1e. -Wl,--as-needed ...\n2.959   collect2         19491  19489    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOLJxkQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.960   collect2         19492  19490    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUIDhKW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n2.961   ld.lld           19493  19491    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOLJxkQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761 ...\n2.962   ld.lld           19494  19492    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUIDhKW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build_script_build-91746dd09f4ff761 ...\n2.962   rust-lld         19493  19491    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccOLJxkQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.964   rust-lld         19494  19492    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccUIDhKW.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n2.998   build-script-bu  19529  19432    0 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build-script-build\n2.998   build-script-bu  19530  19431    0 /target/debug/build/windows_aarch64_msvc-91746dd09f4ff761/build-script-build\n3.003   rustc            19533  19432    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_aarch64_msvc --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=7ca1212926e48158 ...\n3.003   rustc            19534  19431    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name windows_aarch64_msvc --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0c49ab467ef3eabe ...\n6.745   sh               19547  2147557   0 /bin/sh -c which ps\n6.747   which            19547  2147557   0 /usr/bin/which ps\n6.749   sh               19548  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n6.751   ps               19548  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n6.783   sh               19549  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n6.785   cpuUsage.sh      19549  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n6.786   sed              19550  19549    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n6.789   cat              19551  19549    0 /usr/bin/cat /proc/2240539/stat\n6.790   cat              19552  19549    0 /usr/bin/cat /proc/4193716/stat\n6.791   sleep            19553  19549    0 /usr/bin/sleep 1\n7.795   sed              19554  19549    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n7.798   cat              19555  19549    0 /usr/bin/cat /proc/2240539/stat\n7.800   cat              19557  19549    0 /usr/bin/cat /proc/4193716/stat\n8.965   runc             19560  4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1817811637 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n8.972   exe              19567  19560    0 /proc/self/exe init\n8.990   curl             19570  19560    0 /usr/bin/curl -f http://localhost:9091/healthz\n14.022  16               19577  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n14.043  frpc             19577  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n15.941  runc             19584  3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2708877818 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n15.948  exe              19591  19584    0 /proc/self/exe init\n15.968  curl             19593  19584    0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n16.571  16               19600  1        0 /proc/self/fd/16 --deserialize 155 --log-level info --log-target journal-or-kmsg\n16.574  16               19601  1        0 /proc/self/fd/16 --deserialize 182 --log-level info --log-target journal-or-kmsg\n16.739  drkonqi-coredum  19601  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 883-19599-0\n16.744  systemd-coredum  19600  1        0 /usr/lib/systemd/systemd-coredump\n17.274  9                19613  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n17.279  abrt-server      19614  1118     0 /usr/bin/abrt-server -s\n17.292  drkonqi-coredum  19613  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n17.309  abrt-handle-eve  19615  19614    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:31:07.647632-13977\n17.324  runc             19618  15780    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d9 --log-format json --systemd-cgroup kill --all 014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d994e93 9\n17.328  sh               19627  19615    0 /bin/sh -c abrt-action-save-package-data\\n\n17.329  abrt-action-sav  19627  19615    0 /usr/bin/abrt-action-save-package-data\n17.333  runc             19628  15780    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d9 --log-format json --systemd-cgroup delete 014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d994e93\n17.393  sh               19634  19615    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n17.395  cut              19636  19634    0 /usr/bin/cut -d: -f1\n17.395  cat              19637  19635    0 /usr/bin/cat uid\n17.396  getent           19635  19634    0 /usr/bin/getent passwd 1000\n17.397  lscpu            19638  19634    0 /usr/bin/lscpu\n17.414  sh               19639  19615    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n17.416  runlevel         19640  19639    0 /usr/bin/runlevel\n17.427  sh               19641  19615    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n17.429  grep             19642  19641    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n17.431  grep             19643  19641    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n17.432  grep             19644  19641    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n17.434  abrt-action-cor  19645  19641    0 /usr/libexec/abrt-action-coredump -x\n17.456  runc             19647  16017    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764 --log-format json --systemd-cgroup kill --all 9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764336d4 9\n17.464  runc             19653  16017    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764 --log-format json --systemd-cgroup delete 9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764336d4\n17.504  abrt-action-gen  19659  19641    0 /usr/bin/abrt-action-generate-core-backtrace\n17.548  containerd-shim  19660  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d994e93 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d9 delete\n17.551  runc             19666  19660    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d994e9 --log-format json delete --force 014e7c280cc77f759acbb4adb667f4f400b20ad237ccc4394887dad49d994e93\n17.576  abrt-action-ana  19672  19641    0 /usr/bin/abrt-action-analyze-vulnerability\n17.578  eu-readelf       19674  19673    0 /usr/bin/eu-readelf -n coredump\n17.579  sed              19676  19673    0 /usr/bin/sed s/[^0-9]//g\n17.579  grep             19675  19673    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n17.581  gdb              19678  19677    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n17.594  sh               19682  19679    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth53801cd\n17.595  ethtool          19683  19682    0 /usr/sbin/ethtool -i veth53801cd\n17.595  sed              19684  19682    0 /usr/bin/sed -n s/^driver: //p\n17.599  iconv            19687  19678    0 /usr/bin/iconv -l\n17.603  systemd-sysctl   19688  19679    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth53801cd --prefix=/net/ipv4/neigh/veth53801cd --prefix=/net/ipv6/conf/veth53801cd --prefix=/net/ipv6/neigh/veth53801cd\n17.677  containerd-shim  19698  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764336d4 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764 delete\n17.681  runc             19705  19698    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764336d --log-format json delete --force 9422198989d62f711243cac77c8ba483c36e32405c43f9426dbdf4d8764336d4\n17.703  abrt-action-ana  19710  19641    0 /usr/bin/abrt-action-analyze-c\n17.713  systemd-sysctl   19711  19679    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth169ae7b --prefix=/net/ipv4/neigh/veth169ae7b --prefix=/net/ipv6/conf/veth169ae7b --prefix=/net/ipv6/neigh/veth169ae7b\n17.717  eu-unstrip       19712  19710    0 /usr/bin/eu-unstrip --core=./coredump -n\n17.737  abrt-action-lis  19714  19641    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n17.803  cat              19716  19715    0 /usr/bin/cat executable\n17.805  cat              19717  19715    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:31:07.647632-13977/uid\n17.806  journalctl       19718  19715    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n17.820  abrt-action-cor  19719  19641    0 /usr/libexec/abrt-action-coredump -r\n17.881  abrt-handle-eve  19720  19614    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.898  sh               19721  19720    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n17.900  dbus-send        19721  19720    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.902  sh               19722  19720    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n17.903  abrt-action-not  19723  19722    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.975  sh               19724  19723    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n17.977  reporter-system  19724  19723    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n"
    },
    {
      "argv": [
        "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 18054,
      "build_script_target_dir": "slab-b0fe9ec70d8d0253",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build",
      "pid": 18054,
      "ppid": 17898,
      "root_cargo_pid": 17898,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 18054,
      "build_script_target_dir": "slab-b0fe9ec70d8d0253",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 18055,
      "ppid": 18054,
      "root_cargo_pid": 17898,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_1d4b08aa5482ae09_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/slab-3ef8dc27102d261a/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 18054,
      "build_script_target_dir": "slab-b0fe9ec70d8d0253",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 18060,
      "ppid": 18054,
      "root_cargo_pid": 17898,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "slab",
      "cwd": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "event_id": "bsrun:43852cb09115910d:66f198e27447f3ac:8b19fa83fcf83981",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
      "out_dir": "/target/debug/build/slab-b0fe9ec70d8d0253/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
      "success": true,
      "target": null,
      "version": "0.4.9",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-ppc64le-tt_83q7_/src/slab-0.4.9",
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
      "build_script_root_pid": 18054,
      "build_script_target_dir": "slab-b0fe9ec70d8d0253",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 18055,
      "ppid": 18054,
      "root_cargo_pid": 17898,
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
        "autocfg_1d4b08aa5482ae09_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/slab-3ef8dc27102d261a/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 18054,
      "build_script_target_dir": "slab-b0fe9ec70d8d0253",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 18060,
      "ppid": 18054,
      "root_cargo_pid": 17898,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 79,
    "crate": "slab",
    "version": "0.4.9",
    "crate_id": "2392",
    "version_id": "877795",
    "downloads": 222128751,
    "cumulative_downloads": 23490220852,
    "cumulative_share_of_global": 0.08782451291154467,
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
